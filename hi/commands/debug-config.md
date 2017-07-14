# debug:config
वर्तमान व्यवस्था को दिखाएँ।

**Usage:**
```
drupal debug:config [arguments]
dc
```

## Available arguments
Argument | Details
---------|-------------
name | व्यवस्था नाम।

## Examples
* List all configuration object names.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* List all system configuration names.
```
drupal config:debug | grep system
```
