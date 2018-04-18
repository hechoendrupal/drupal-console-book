# config:export:content:type
Exportați un anumit tip de conținut și câmpurile aferente acestuia.

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--optional-config | Exportați tipul de conținut ca și un fișier opțional de configurare YAML în modulul dvs.
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Available arguments
Argument | Details
---------|-------------
content-type | Content Type to be exported

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
