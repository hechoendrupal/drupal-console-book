# debug:container
サービスを表示

**Usage:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Available options
Option | Details
-------|-------------
--parameters | サービス名
--tag | Service tag 

## Available arguments
Argument | Details
---------|-------------
service | サービス名
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
