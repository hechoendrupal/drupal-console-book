# generate:module Options
The **generate:module** command helps you generate a new module.

```
$ drupal g:module --help
```
**Usage:**
```
 generate:module [--module="..."] [--machine-name="..."] [--module-path="..."] [--description[="..."]] [--core[="..."]] [--package[="..."]] [--controller] [--dependencies[="..."]] [--test]
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
--help (-h)  |   Display this help message
--quiet (-q)  |  Do not output any message
**--verbose** (-v) | Show more verbose messages
--vv |Increase the verbosity of messages
--vvv | Debug mode verbosity
--version (-V)   |   Display this application version
--ansi  |  Force ANSI output
--no-ansi  |   Disable ANSI output
--no-interaction (-n) |  Do not ask any interactive question
--drupal (-d)  |   Path to Drupal root.
--shell (-s)  |  Launch the shell.
--env (-e)   |   The Environment name. (default: "prod")
--no-debug   |   Switches off debug mode.
--learning   |   Generate a verbose code output.
