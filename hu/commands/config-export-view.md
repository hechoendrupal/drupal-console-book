# config:export:view
The **config:export:view** command Exportáljon egy view-t YAML formátumban, egy adott modulon belül amit más siteokon újrahasználhat.

**Usage:**
```
$ drupal config:export:view [arguments] [options] 
$ cev  
```

## Available options
Option | Details
-------|-------------
--module | A Modul neve.
--optional-config | Vew exportálása a modulodba opciónális YAML konfigurációs fájlként
--include-module-dependencies | Modul függőségek becsatolása a modul YAML info fájljába 

## Available arguments
Argument | Details
---------|-------------
view-id | View ID
