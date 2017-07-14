# config:export
Exporta la configuración actual de la aplicación.

**Usage:**
```
drupal config:export [options]
ce
```

## Available options
Option | Details
-------|-------------
--directory | Define el directorio de exportación donde guardar la salida de la configuración.
--tar | Si se indica, la configuración será exportada a un archivo.
--remove-uuid | Si se indica, la configuración será exportada sin la clave uuid.
--remove-config-hash | Si se indica, la configuración será exportada sin la clave hash del sitio por defecto.

## Examples
* Optional you can add the path to export
```
drupal config:export  \
  --directory="path/to/export"
```
* If export will be in a compressed file and/or if uuid and config hashes will be removed.
```
drupal config:export  \
  --directory="path/to/export" \
  --tar \
  --remove-uuid \
  --remove-config-hash
```
