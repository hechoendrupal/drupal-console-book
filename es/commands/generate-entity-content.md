# generate:entity:content
Generar una nueva entidad de contenido

**Uso:**
```
drupal generate:entity:content [options]
geco
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--entity-class | Clase de la entidad de contenido
--entity-name | Nombre de la entidad de contenido
--base-path | El directorio raíz para las rutas de la entidad de contenido
--label | Etiqueta
--has-bundles | La entidad tiene bundles
--is-translatable | Entidad de contenido traducible
--revisionable | commands.generate.entity.content.options.revisionable

## Ejemplos
* Generar una entidad de contenido especificando el módulo, la clase de entidad, el nombre de entidad, su ruta y la etiqueta
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* Generar una entidad de contenido con revisiones y traducible especificando el módulo, la clase de entidad, el nombre de entidad, la ruta, y su etiqueta
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
