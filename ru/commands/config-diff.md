# config:diff
The **config:diff** command Ouput configuration items that are different in active configuration compared with a directory.

**Использование:**
```
$ drupal config:diff [arguments] [options]
```

## Доступные опции
Опция | Описание
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## Доступные параметры
Параметр | Описание
---------|-------------
directory | The directory to diff against. If ommitted, choose from Drupal config directories.
