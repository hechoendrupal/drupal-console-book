# config:import:single
Importar la configuración seleccionada.

**Uso:**
```
drupal config:import:single [options]
cis
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--file | El nombre del fichero o la ruta absoluta del archivo a importar
--directory | commands.config.import.arguments.directory

## Ejemplos
* Facilitando una opción File usando la ruta absoluta.
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Facilitando las opciones File y Directory
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```
