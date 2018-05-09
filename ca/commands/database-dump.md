# database:dump
Còpia de seguretat d'estructura, continguts i taules de la base de dades MySQL

**Ús:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--file |  Nom del fitxer de la còpia de la base de dades
--gz | Pass this option if you want the sql result file gzipped

## Arguments disponibles
Argument | Detalls
---------|-------------
database | Clau de la base de dades des de settings.php

## Exemples
* Dump default database or the one specified on the argument
```
drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
drupal database:dump \
  --gz
```
