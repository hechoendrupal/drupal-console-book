# rest:debug
The **rest:debug** command displays current migration available for the application

```
$ drupal rest:debug --help
```
**Usage:**
```
 rest:debug [--authorization[="..."]] [resource-id]
```
## Arguments
Argument | Details
------------ |-------------
 resource-id  |         Rest ID

## Available options
Options | Details
------------ |-------------
 --authorization |      REST resource status enabled / disabled
--help (-h)     |       Display this help message
--quiet (-q)    |      Do not output any message
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
