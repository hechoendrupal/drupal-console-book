# generate:plugin:rulesaction Options
  The **generate:plugin:rulesaction** command helps you generate a new Rules action plugin.

```
$ drupal g:p:rulesaction --help
```
**Usage:**
```
 generate:plugin:rulesaction [--module="..."] [--class-name[="..."]] [--label[="..."]] [--plugin-id[="..."]] [--category[="..."]] [--context[="..."]]
```
## Available options
Options | Details
------------ |-------------
--module    |          The Module name.
--class-name |         Plugin class name
--label       |        Plugin label
--plugin-id    |       Plugin id
--category     |       Plugin category (multiple values allowed)
--context       |      Plugin context
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
