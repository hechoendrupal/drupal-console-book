# generate:module
Generează un modul.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului
--machine-name | Numele mașină (doar minuscule și liniuțe jos)
--module-path | Calea către modul
--description | Descrierea modulului
--core | Versiunea nucleului
--package | Pachetul modulului
--module-file | Add a .module file
--features-bundle | Define module as feature using the given Features bundle name
--composer | Adaugă un fișier composer.json
--dependencies | Dependințele modulului trebuie să fie separate prin virgulă (ex. context, panels)
--test | Generează o clasă pentru testare
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
