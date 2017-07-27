# config:export
Exporta la configuración actual de la aplicación.

**Uso:**
```
drupal config:export [options]
ce
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--directory | Define el directorio de exportación donde guardar la salida de la configuración.
--tar | Si se indica, la configuración será exportada a un archivo.
--remove-uuid | Si se indica, la configuración será exportada sin la clave uuid.
--remove-config-hash | Si se indica, la configuración será exportada sin la clave hash del sitio por defecto.

## Ejemplos
* Opcionalmente, puede añadir la ruta donde exportar
```
drupal config:export  \
  --directory="path/to/export"
```
* Volcar la exportación en un archivo comprimido y eliminar el uuid y los hashes de configuración.
```
drupal config:export  \
  --directory="path/to/export" \
  --tar \
  --remove-uuid \
  --remove-config-hash
```
