# debug:state
列出現有系統狀態鍵名

**Usage:**
```
drupal debug:state [arguments]
dst
```

## Available arguments
Argument | Details
---------|-------------
key | 要查詢的系統狀態鍵名。

## Examples
* List of the states on the site
```
drupal debug:state
```
* Displays a detail of the state install_task tok from the list of states
```
drupal debug:state install_task
```
