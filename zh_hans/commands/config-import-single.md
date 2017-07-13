# config:import:single
Import a single configuration or a list of configurations.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:import:single [options]
$ cis  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | The file(s) name or file(s) absolute path to import
--directory | commands.config.import.arguments.directory

## commands.generate.doc.gitbook.messages.examples
* Providing a file option using full path.
```
$ drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Providing file and directory options
```
$ drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"

```
