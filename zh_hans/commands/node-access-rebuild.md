# node:access:rebuild
Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.

**用法:**
```
$ drupal node:access:rebuild [options]
```

## 可用选项
选项 | 详细
-------|-------------
--batch | Process in batch mode.

## 例子
* Rebuild node access permissions
```
$ drupal node:access:rebuild --batch
```
