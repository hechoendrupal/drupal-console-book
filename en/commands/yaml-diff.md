# yaml:diff
commands.generate.doc.output.command.command_description

**commands.generate.doc.output.command.usage:**
```
$ drupal yaml:diff [arguments] [options] 
```

## commands.generate.doc.output.command.options
commands.generate.doc.output.command.options | commands.generate.doc.output.command.details
-------|-------------
--negate | Define mode diff or equal comparation, possible values TRUE/FALSE or 0/1
--limit | Limit results to a specific number
--offset | Starting point of a limit

## commands.generate.doc.output.command.arguments
commands.generate.doc.output.command.argument | commands.generate.doc.output.command.details
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to determine missing or differences with base YAML file
