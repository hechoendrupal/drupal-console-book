# config:import:single
Importar a configuratição selecionada.

**Utilização:**
```
drupal config:import:single [options]
cis
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--file | The file(s) name or file(s) absolute path to import
--directory | commands.config.import.arguments.directory

## Exemplos
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
