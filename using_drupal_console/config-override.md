# config:override
The **config:override** command overrides the config value in active configuration

```
$ drupal config:override --help
```
**Usage:**
```
config:override config-name key value
```
## Arguments
Argument | Details
------------ |-------------
config-name  |         Configuration name.
key          |         Key
value        |         Value

## Available options
Options | Details
------------ |-------------
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
