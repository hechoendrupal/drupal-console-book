# debug:container
显示当前服务

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | 服务名称

## Available arguments
Argument | Details
---------|-------------
service | 服务名称
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
