# settings:set
Change a specific setting value in DrupalConsole config file

**Usage:**
```
drupal settings:set [arguments]
```

## Available arguments
Argument | Details
---------|-------------
name | Setting name in YAML flatten format to set a value in Drupal Console config file
value | Setting value to set in Drupal Console config file

## Examples
* Set application language setting value to "es"
```
drupal settings:set  application.language es
```
