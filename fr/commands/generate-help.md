# generate:help
Génère une implémentation de hook_help()

**Usage:**
```
drupal generate:help [options]
gh
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--description | Description du module

## Examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
