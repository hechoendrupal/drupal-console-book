# debug:container
Отображает текущие сервисы для приложения.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | Имя сервиса.

## Available arguments
Argument | Details
---------|-------------
service | Имя сервиса.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
