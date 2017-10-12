# Generando código con un comando

Para generar código desde un comando, debe realizar tres pasos:

1. [Crear una plantilla Twig para el código que quiera generar.](#twig-template)
2. [Crear y registrar un servicio personalizado Generator para renderizar la plantilla Twig.](#generator-service)
3. [Inyectar el servicio personalizado Generator en su comando.](#inject-service)

<a name="twig-template"></a>
## Creando una plantilla Twig para el código generado

Todas las plantilllas Twig deben estar situadas dentro de un subdirectorio  `templates`
de su módulo o extensión. Por ejemplo:

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
## Creando un servicio personalizado de Generator

Para crear un servicio personalizado Generator, primero cree una clase que extienda de
`Drupal\Console\Core\Generator\Generator`. Por ejemplo:

`src/Generator/ModuleGenerator`

```
namespace Drupal\your_extension\Generator;

use Drupal\Console\Core\Generator\Generator;

class ModuleGenerator extends Generator
{
  ...
}
```

Use el método `renderFile()` heredado de la clase `Generator` para renderizar su template Twig.

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

Finalmente, registre su clase Generator como un servicio personalizado en `console.services.yml`.

```
services:
  your_extension.module_generator:
    class: Drupal\your_extension\Generator\ModuleGenerator
    tags:
      - { name: drupal.generator }
```

Asegúrese de incluir la etiqueta `drupal.generator` para que el renderizador de Twig sea inicializado propiamente.

<a name="inject-service"></a>
## Inyectando la clase Generator personalizada en su comando

En `console.services.yml`, añada su servicio personalizado Generator como argumento de su comando personalizado.

```
services:
  your_extension.generate_module:
    class: Drupal\your_extension\Command\Generate\ModuleCommand
    arguments: ['@your_extension.module_generator']
    tags:
       - { name: drupal.command }
```

Y añada su Generator personalizado al los parámetros del constructor de su clase de comando:

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

Ahora puede llamar a su Generator desde el método `execute()` en su comando para producir los archivos de código renderizados:

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
