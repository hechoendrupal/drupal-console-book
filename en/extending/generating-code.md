# Generating Code with a Command

To generate code from a Command, there are three steps:

1. [Create a Twig template for the code you want to generate.](#twig-template)
2. [Create and register a custom Generator service for rendering 
the Twig template.](#generator-service)
3. [Inject the custom Generator service into your Command.](#inject-service)

<a name="twig-template"></a>
## Creating a Twig Template for the Generated Code

All Twig templates should be placed inside a `templates` subdirectory 
of your module or extension. For example:

`templates/module/info.yml.twig`

```
name: {{ module }}
type: {{ type }}
description: {{ description }}
core: {{ core }}
package: {{ package }}
{% if dependencies %}
dependencies:
{% for dependency in dependencies %}
  - {{ dependency }}
{% endfor %}
{% endif %}
```
<a name="generator-service"></a>
## Creating a Custom Generator Service

To create a custom Generator service, first create a class that extends from 
`Drupal\Console\Core\Generator\Generator`. For example:

`src/Generator/ModuleGenerator`

```
namespace Drupal\your_extension\Generator;

use Drupal\Console\Core\Generator\Generator;

class ModuleGenerator extends Generator
{
  ...
}
```

Use the `renderFile()` method inherited from the `Generator` class to render 
your Twig template.

```
public function generate($module, $machineName, $output_dir, $description, $core, $package, $dependencies) {

  $parameters = [
    'module' => $module,
    'core' => $core,
    'description' => $description,
    'package' => $package,
    'dependencies' => $dependencies,
  ];

  $this->renderFile(
    'module/info.yml.twig',
    $output_dir.'/'.$machineName.'.info.yml',
    $parameters
  );

}
```

Finally, register your Generator class as a custom service in `console.services.yml`.

```
services:
  your_extension.module_generator:
    class: Drupal\your_extension\Generator\ModuleGenerator
    tags:
      - { name: drupal.generator }
```

Be sure to include the `drupal.generator` tag so that the Twig renderer is properly 
initialized.

<a name="inject-service"></a>
## Injecting Your Custom Generator Into Your Command

In `console.services.yml`, add your custom Generator service as an argument for your 
custom Command.

```
services:
  your_extension.generate_module:
    class: Drupal\your_extension\Command\Generate\ModuleCommand
    arguments: ['@your_extension.module_generator']
    tags:
       - { name: drupal.command }
```

And add your custom Generator to the constructor parameters for your Command class:

```
use Drupal\your_extension\Generator\ModuleGenerator;

class ModuleCommand extends Command
{
  /**
   * ModuleCommand constructor.
   *
   * @param \Drupal\your_extension\Generator\ModuleGenerator $generator
   */
  public function __construct(ModuleGenerator $generator) {
    $this->generator = $generator;
    parent::__construct();
  }
   
  ...
}
```

You can now call your Generator from the `execute()` method in your Command 
to output rendered code files:

```
protected function execute(InputInterface $input, OutputInterface $output) {
  
  ...
  
  $this->generator->generate(
    $module,
    $machineName,
    $modulePath,
    $description,
    $core,
    $package,
    $dependencies
  );
  
}
```
