# generate:controller Options
The **generate:controller** command helps you generate a new controller.

```
$ drupal g:controller --help
```
## Usage:
```
generate:controller [--module="..."] [--class-name[="..."]] [--method-name[="..."]] [--route[="..."]] [--services[="..."]] [--test]
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
--help (-h)     |       Display this help message
--quiet (-q)     |      Do not output any message
**--verbose** (-v) | Show more verbose messages
--vv | Increase the verbosity of messages
--vvv | Debug mode verbosity
--version (-V)    |     Display this application version
--ansi             |    Force ANSI output
--no-ansi          |    Disable ANSI output
--no-interaction (-n)  | Do not ask any interactive question
--drupal (-d)      |    Path to Drupal root.
--shell (-s)       |    Launch the shell.
--env (-e)         |    The Environment name. (default: "prod")
--no-debug         |    Switches off debug mode.
--learning         |    Generate a verbose code output.

## Help:
```
 commands.generate.controller.command.help
```
