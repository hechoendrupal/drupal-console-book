# yaml:diff
The **yaml:diff** command Két YAML-fájl összehasonlítása a közöttük lévő különbségek megkereséséhez.

**Usage:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## Available options
Option | Details
-------|-------------
--stats | Statisztika nyomtatása a YAML-fájlok összehasonlításáról
--negate | Különbözők vagy azonosak összehasonlítása, a lehetséges értékek TRUE/FALSE vagy 0/1
--limit | Egy adott számra korlátozza a találatok számát
--offset | Egy korlát kezdőpontja

## Available arguments
Argument | Details
---------|-------------
yaml-left | Az összehasonlítás alapjául használt YAML-fájl
yaml-right | Az alap YAML-fájlhoz képest előforduló különbségek vagy hiányzó részek megkeresésére használt YAML-fájl
