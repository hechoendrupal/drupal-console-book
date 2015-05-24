# generate:command Options
The **generate:command** command helps you to generate a new command.

```
$ drupal generate:command --help
```
**Usage:**
```
$ drupal generate:command [--module="..."] [--class-name[="..."]] [--command[="..."]] [--container]
```
## Available options
Options | Details
------------ |-------------
--module        |       The Module name.
--class-name    |      Command Class name
--command       |       Command name
--container     |       Access the services container
--services      |       Load services from the container. (multiple values allowed)
