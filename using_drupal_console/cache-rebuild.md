# cache:rebuild
The **cache:rebuild** command rebuilds and clears all site caches

```
$ drupal c:r --help
```
**Usage:**
```
cache:rebuild [--cache[="..."]]
```
## Available options
Options | Details
------------ |-------------
--cache       |        Only clear a specific cache. (default: "")
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
