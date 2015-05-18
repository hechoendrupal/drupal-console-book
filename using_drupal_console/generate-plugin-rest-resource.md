# generate:plugin:block Options
 The generate:plugin:rest:resource command helps you generate a new rest resource.

```
$ drupal g:p:r:r --help
```
**Usage:**
```
 generate:plugin:rest:resource [--module="..."] [--class-name[="..."]] [--plugin-id[="..."]] [--plugin-label[="..."]] [--plugin-url[="..."]] [--plugin-states[="..."]]
```
## Available options
Options | Details
------------ |-------------
--module     |         The Module name.
--class-name |        Plugin Rest Resource class
--plugin-id   |        Plugin Rest Resource id
--plugin-label |       Plugin Rest Resource Label
--plugin-url    |      Plugin Rest Resource URL (multiple values allowed)
--plugin-states  |     Plugin Rest Resource States (multiple values allowed)
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
