# debug:container
अनुप्रयोग चालू सेवा दाखवा.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | सेवेचे नाव.

## Available arguments
Argument | Details
---------|-------------
service | सेवेचे नाव.
method | पद्धत नाव
arguments | CSV किंवा JSON स्वरूपातील वितर्कांचा अॅरे.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
