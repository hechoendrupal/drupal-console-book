# module:update
Update core, module or modules in the application

**Használat:**
```
$ drupal module:update [arguments] [options]
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.
