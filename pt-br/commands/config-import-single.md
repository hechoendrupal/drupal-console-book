# config:import:single
Importar a configuratição selecionada.

**application.gitbook.messages.usage:**
```
drupal config:import:single [options]
cis
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | The file(s) name or file(s) absolute path to import
--directory | Path to a directory of configuration to import.

## application.gitbook.messages.examples
* Providing a file option using full path.
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Providing file and directory options
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```
