# generate:command Options
The **generate:command** command helps you to generate a new command.

```
$ drupal g:command --help
```
**Usage:**
```
 generate:command [--module="..."] [--class-name[="..."]] [--command[="..."]] [--container]
```
## Available options
Options | Details
------------ |-------------
--module        |       The Module name.
--class-name    |      Command Class name
--command       |       Command name
--container     |       Access the services container
--services      |       Load services from the container. (multiple values allowed)
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
