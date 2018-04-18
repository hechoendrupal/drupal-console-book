# config:export:content:type
Adott tartalomtípus és mezőinek exportálása.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--optional-config | Tartalomtípus exportálása a modulba nem kötelező YAML-konfigurációként
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Available arguments
Argument | Details
---------|-------------
content-type | Az exportálni kívánt tartalomtípus

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
