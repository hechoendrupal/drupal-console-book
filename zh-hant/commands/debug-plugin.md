# debug:plugin
顯示全部外掛模組資訊，包含外掛類型、指定類別的外掛實體，或是指定外掛的定義說明

**Usage:**
```
drupal debug:plugin [arguments]
dpl
```

## Available arguments
Argument | Details
---------|-------------
type | 外掛類型
id | 外掛 ID

## Examples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
