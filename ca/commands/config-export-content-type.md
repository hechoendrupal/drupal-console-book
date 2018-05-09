# config:export:content:type
Exportar un tipus de contingut i els seus camps.

**Ús:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--optional-config | Exportar tipus de contingut com un fitxer de configuració opcional YAML en el teu mòdul
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Arguments disponibles
Argument | Detalls
---------|-------------
content-type | El tipus de contingut que serà exportat

## Exemples
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
