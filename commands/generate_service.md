# generate:service Options
The **generate:service** command is used to generate a new service.

```
$ drupal generate:service --help
```
**Usage:**
```
$ generate:service [--module="..."] [--service-name[="..."]] [--class-name[="..."]] [--interface[="..."]] [--services[="..."]]
```
**Aliases:**
```
$ drupal g:s --help
```
## Available options
Options | Details
------------ |-------------
--module     |          The Module name.
--service-name  |       Service name
--class-name   |        Class name
--interface    |        commands.common.service.options.interface
--services      |       Load services from the container. (multiple values allowed)
