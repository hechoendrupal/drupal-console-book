# config:diff
**config:diff** 命令 Ouput configuration items that are different in active configuration compared with a directory.

**用法:**
```
$ drupal config:diff [arguments] [options] 
```

## 可用选项
选项 | 详细
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## 可用参数
参数 | 详细
---------|-------------
directory | The directory to diff against. If ommitted, choose from Drupal config directories.
