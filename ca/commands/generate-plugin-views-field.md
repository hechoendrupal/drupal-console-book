# generate:plugin:views:field
Generar un connector de camp de vista predeterminat.

**Ús:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Nom de la classe del connector del camp de vista
--title | Títol del connector de camp de vista
--description | Descripció del connector de camp de vista

## Exemples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
