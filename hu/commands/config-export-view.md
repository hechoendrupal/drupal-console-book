# config:export:view
Nézet exportálása YAML-formátumban egy megadott modulba, hogy újra lehessen használni más weboldalon.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--optional-config | Nézet exportálása a modulba nem kötelező YAML-konfigurációként
--include-module-dependencies | Modulfüggőségeinek tartalmazása a modul info.yml fájljában

## Available arguments
Argument | Details
---------|-------------
view-id | Nézet azonosítója

## Examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
