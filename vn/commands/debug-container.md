# debug:container
Các dịch vụ hiển thị hiện tại cho một ứng dụng

**Usage:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Available options
Option | Details
-------|-------------
--parameters | Service name.
--tag | Service tag 

## Available arguments
Argument | Details
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
