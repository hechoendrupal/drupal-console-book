# config:export:view
Exportă un view în format YAML în interiorul unui modul furnizat pentru a-l reutiliza în alt sit web.

**Usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--optional-config | Exportați view-ul ca și o configurare YAML opțională în modulul dvs.
--include-module-dependencies | Includeți dependințele modulului în fișierul info YAML al modulului

## Available arguments
Argument | Details
---------|-------------
view-id | ID-ul view-ului

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
