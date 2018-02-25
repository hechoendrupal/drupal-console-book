# config:export:content:type
Exporta un tipo de contenido específico y sus campos.

**Uso:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--optional-config | Exportar tipo de contenido como un fichero de configuración YAML opcional en tu módulo
--remove-uuid | Si se da, la configuración será exportada sin clave uuid.
--remove-config-hash | Si se da, la configuración será exportada sin la clave has por defecto del sitio.

## Argumentos disponibles
Argumento | Detalles
---------|-------------
content-type | Tipo de contenido a exportar

## Ejemplos
* Puede facilitar un nombre de módulo para la exportación del tipo de contenido
```
drupal config:export:content:type page \
  --module="demo"
```
* Si desea exportar un tipo de contenido facilitando la configuración opcional y el nombre del módulo
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
