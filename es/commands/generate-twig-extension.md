# generate:twig:extension
Generar una extensión de Twig.

**Uso:**
```
drupal generate:twig:extension [options]
gte
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--name | Nombre de la extensión Twig
--class | Nombre de la clase
--services | Cargar servicios desde el contenedor.

## Ejemplos
* Generar una extensión de Twig especificando el nombre del módulo, el nombre de extensión y su clase
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
