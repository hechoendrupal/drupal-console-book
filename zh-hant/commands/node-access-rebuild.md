# node:access:rebuild
重建內容存取權限。重建過程將移除現有權限並依照目前模組與設定取代成為新權限。

**Usage:**
```
drupal node:access:rebuild [options]
nar
```

## Available options
Option | Details
-------|-------------
--batch | 以批次方式執行

## Examples
* 重建內容存取權限
```
drupal node:access:rebuild --batch
```
