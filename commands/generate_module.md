# generate:module Options
The **generate:module** command helps you generate a new module.

```
$ drupal generate:module --help
```
**Usage:**
```
 $ drupal generate:module [--module="..."] [--machine-name="..."] [--module-path="..."] [--description[="..."]] [--core[="..."]] [--package[="..."]] [--controller] [--dependencies[="..."]] [--test]
```
## Available options
Options | Details
------------ |-------------
--module   |   The Module name
--machine-name  |  The machine name (lowercase and underscore only)
--module-path  |   The path of the module
--description  |   Module description
--core   |   Core version
--package  |   Module package
--controller  |  Default Controller
--dependencies   |   Module dependencies separated by commas (i.e. context, panels)
--test   |   Generate a test class
