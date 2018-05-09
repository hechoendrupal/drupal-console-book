# debug:container
Affiche les services actuels d'une application.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Available options
Option | Details
-------|-------------
--parameters | Nom du service.
--tag | Service tag 

## Available arguments
Argument | Details
---------|-------------
service | Nom du service.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
