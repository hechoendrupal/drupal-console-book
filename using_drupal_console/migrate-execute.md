# migrate:execute
The **migrate:execute** command executes an available migration

```
$ drupal migrate:execute --help
```
**Usage:**
```
migrate:execute [--site-url="..."] [--db-host="..."] [--db-name="..."] [--db-user="..."] [--db-pass[="..."]] [--db-prefix[="..."]] [--db-port="..."] migration-id
```
## Arguments
Argument | Details
------------ |-------------
migration-id   |       Migration Id

## Available options
Options | Details
------------ |-------------
--site-url   |         Site Source URL
--db-host    |         Database Host
--db-name    |         Database Name
--db-user    |         Database User
--db-pass    |         Database Pass
--db-prefix  |         Database Prefix
--db-port    |         Database Port
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
