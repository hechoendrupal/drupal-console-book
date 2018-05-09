# generate:help
Generate an implementation of hook_help()

**Ús:**
```
drupal generate:help [options]
gh
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--description | commands.generate.help.options.description

## Exemples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
