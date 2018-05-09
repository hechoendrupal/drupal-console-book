# debug:container
Mostrar els serveis actuals de l'aplicació.

**Ús:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--parameters | Service name.
--tag | Service tag 

## Arguments disponibles
Argument | Detalls
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Exemples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
