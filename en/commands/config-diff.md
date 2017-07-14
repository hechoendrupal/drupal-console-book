# config:diff
Output configuration items that are different in active configuration compared with a directory.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## Available arguments
Argument | Details
---------|-------------
directory | The directory to diff against. If omitted, choose from Drupal config directories.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
