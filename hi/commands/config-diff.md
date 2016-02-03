# config:diff
**config:diff** कमांड Ouput configuration items that are different in active configuration compared with a directory.

**प्रयोग:**
```
$ drupal config:diff [arguments] [options] 
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--reverse | See the changes in reverse (i.e diff a directory to the active configuration).

## उपलब्ध तर्कों
तर्क | विवरण
---------|-------------
directory | The directory to diff against. If ommitted, choose from Drupal config directories.
