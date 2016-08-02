# config:diff
Ouput configuration items that are different in active configuration compared with a directory.

**使い方:**
```
$ drupal config:diff [arguments] [options]
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## 利用可能な引数
引数 | 詳細
---------|-------------
directory | The directory to diff against. If omitted, choose from Drupal config directories.
