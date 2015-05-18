# module:debug
The **module:debug** command displays status and origin info for each available module

```
$ drupal module:debug --help
```
**Usage:**
```
module:debug [--status[="..."]] [--type[="..."]]
```

## Available options
Options | Details
------------ |-------------
--status     |         Module status [enabled|disabled]
--type       |         Module type [core|no-core]
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
