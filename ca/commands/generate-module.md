# generate:module
Generar un mòdul

**Ús:**
```
drupal generate:module [options]
gm
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul
--machine-name | Nom màquina del mòdul (només minúscules i caràcter de subratllat)
--module-path | Camí del mòdul
--description | Descripció del mòdul
--core | Versió del core
--package | Paquet del mòdul
--module-file | Afegir un fitxer .module
--features-bundle | Define module as feature using the given Features bundle name
--composer | Afegir fitxer composer.json
--dependencies | Dependències del mòdul separades per comes (p.e. context, panels)
--test | Generar classe de verificació
--twigtemplate | Generate theme template

## Exemples
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
