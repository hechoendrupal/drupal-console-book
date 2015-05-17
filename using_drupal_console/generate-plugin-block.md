# generate:plugin:block Options
 The **generate:plugin:block** command helps you generate a new Plugin block.

```
$ drupal g:p:b --help
```
**Usage:**
```
 generate:plugin:block [--module="..."] [--class-name[="..."]] [--label[="..."]] [--plugin-id[="..."]] [--inputs[="..."]] [--services[="..."]]
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
