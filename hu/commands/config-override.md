# config:override
Az aktív konfiguráció értékének felülbírálása.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | Kulcs
value | Érték

## Examples
* A Contact modul elárasztási korlátjának beállítása 10 értékre.
```
drupal config:override contact.settings flood.limit 10
```
