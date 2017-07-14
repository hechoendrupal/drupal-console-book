# generate:module
Modul létrehozása.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | A modul neve
--machine-name | A programok által használt név (csak kisbetűk és aláhúzás)
--module-path | A modul útvonala
--description | A modul leírása
--core | Drupal alaprendszer verziója
--package | Modulcsomag
--module-file | .module fájl hozzáadása
--features-bundle | Define module as feature using the given Features bundle name
--composer | composer.json fájl hozzáadása
--dependencies | Modulfüggőségek vesszővel elválasztva (pl. context, panels)
--test | Tesztosztály létrehozása
--twigtemplate | Generate theme template

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
