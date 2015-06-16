# generate:plugin:block Options
 The **generate:plugin:block** command helps you generate a new Plugin block.

```
$ drupal generate:plugin:block --help
```
**Usage:**
```
$ drupal generate:plugin:block [--module="..."] [--class-name[="..."]] [--label[="..."]] [--plugin-id[="..."]] [--inputs[="..."]] [--services[="..."]]
```
**Aliases:
```
$ drupal g:p:b --help
```
## Available options
Options | Details
------------ |-------------
--module    |          The Module name.
--class-name |         Plugin class name
--label       |        Plugin label
--plugin-id    |       Plugin id
--inputs      |        Create inputs in a form. (multiple values allowed)
--services     |       Load services from the container.
