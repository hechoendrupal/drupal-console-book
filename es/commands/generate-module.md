# generate:module
Generar un módulo.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | El nombre del módulo
--machine-name | El nombre máquina (sólo minúsculas y guión bajo)
--module-path | El directorio del módulo
--description | Descripción del módulo
--core | Versión del core
--package | Paquete del módulo
--module-file | Agregar un archivo .module
--features-bundle | ¿ Definir el módulo como una feature usando el nombre de bundle de Feature dado ?
--composer | Añadir un archivo composer.json
--dependencies | Dependencias del módulo (por ejemplo: context, galleria, panels)
--test | Generar una clase de test
--twigtemplate | Generar plantilla de theme

## Examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
