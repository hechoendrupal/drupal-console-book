# generate:controller Options
The **generate:controller** command helps you generate a new controller.

```
$ drupal generate:controller --help
```
## Usage:
```
$ drupal generate:controller [--module="..."] [--class-name[="..."]] [--method-name[="..."]] [--route[="..."]] [--services[="..."]] [--test]
```
## Available options:
Options | Details
------------ |-------------
--module      |        The Module name.
--class-name  |         Controller Class name
--method-name |         The action method name
--route       |         The route path
--services    |         Load services from the container. (multiple values allowed)
--test        |         Generate a test class
