# generate:form:config Options
The **generate:form:config** command helps you generate a new "ConfigFormBase".

```
$ drupal g:f:c --help
```
**Usage:**
```
generate:form:config [--module="..."] [--class-name[="..."]] [--form-id[="..."]] [--services[="..."]] [--inputs[="..."]] [--routing]
```
## Available options
Options | Details
------------ |-------------
--module     |          The Module name.
--class-name   |        Class name
--form-id      |       The Form id
--services      |      Load services from the container.
--inputs         |     Create inputs in a form.
--routing         |    Update routing
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
