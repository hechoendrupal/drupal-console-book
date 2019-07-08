# تولید کد با یک دستور

برای تولید کد از یک دستور، سه گام وجود دارد:

1. [ایجاد یک قالب Twig برای کدی که می‌خواهید تولید کنید.](#twig-template)
2. [ایجاد و ثبت یک سرویس Generator سفارشی برای پردازش قالب Twig.](#generator-service)
3. [قراردادن سرویس Generator سفارشی درون دستور](#inject-service)

<a name="twig-template"></a>
## ایجاد یک قالب Twig برای کد تولید شده

تمام قالب‌های Twig باید درون یک دایرکتوری `templates` از زیرمجموعه افزونه شما قرار بگیرند. برای نمونه:

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
## ایجاد یک سرویس Generator سفارشی

برای ایجاد یک سرویس Generator سفارشی، ابتدا کلاسی ایجاد کنید که از `Drupal\Console\Core\Generator\Generator` تبعیت می‌کند. برای نمونه:

`src/Generator/ModuleGenerator`

```
namespace Drupal\your_extension\Generator;

use Drupal\Console\Core\Generator\Generator;

class ModuleGenerator extends Generator
{
  ...
}
```

با استفاده از متد `renderFile()`، که از کلاس `Generator` به ارث رسیده است، قالب Twig خود را پردازش کنید.

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

در نهایت، کلاس Generator خود را به عنوان یک سرویس سفارشی درون `console.services.yml` ثبت کنید.

```
services:
  your_extension.module_generator:
    class: Drupal\your_extension\Generator\ModuleGenerator
    tags:
      - { name: drupal.generator }
```

اطمینان یابید که برچسب `drupal.generator` وارد شده باشد تا پردازشگر Twig به صورت صحیح راه‌اندازی گردد.

<a name="inject-service"></a>
## قراردادن سرویس Generator سفارشی درون دستور

درون `console.services.yml`، سرویس Generator سفارشی را به عنوان یک آرگومان برای دستور خود قرار دهید.

```
services:
  your_extension.generate_module:
    class: Drupal\your_extension\Command\Generate\ModuleCommand
    arguments: ['@your_extension.module_generator']
    tags:
       - { name: drupal.command }
```

و Generator سفارشی را درون پارامتر constructor از کلاس Command قرار دهید.

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

اکنون می‌توانید Generator را از متد `execute()` دستور خود فراخوانی کنید تا فایل‌های مورد نیاز پردازش گردند.

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
