# generate:entity:bundle
Genera un nuevo tipo de contenido (nodo / bundle de entidad)

**Uso:**
```
drupal generate:entity:bundle [options]
geb
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--bundle-name | El nombre máquina del tipo de contenido
--bundle-title | El nombre amigable del tipo de contenido

## Ejemplos
* Generar un nuevo tipo de contenido especificando el módulo, el nombre del bundle y su título
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
