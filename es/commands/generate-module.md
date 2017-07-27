# generate:module
Generar un módulo.

**Uso:**
```
drupal generate:module [options]
gm
```

## Opciones disponibles
Opción | Detalles
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

## Ejemplos
* Generar un módulo especificando el nombre del módulo, el nombre máquina, la ruta, su descripción, el core de Drupal y el nombre del paquete. En este ejemplo se generan también el archivo de composer, el test unitario y la plantilla de Twig
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
