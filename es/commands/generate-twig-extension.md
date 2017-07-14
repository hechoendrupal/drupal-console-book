# generate:twig:extension
Generar una extensión de Twig.

**Usage:**
```
drupal generate:twig:extension [options]
gte
```

## Available options
Option | Details
-------|-------------
--module | Nombre del módulo.
--name | Nombre de la extensión Twig
--class | Nombre de la clase
--services | Cargar servicios desde el contenedor.

## Examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
