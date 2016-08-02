# yaml:diff
Comparar dos fitxers YAML.

**Ús:**
```
$ drupal yaml:diff [arguments] [options]
$ yd  
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--stats | Imprimir estadístiques de la comparació de fitxer YAML
--negate | Defineix el mode de comparació (diff) o igual (equal), valors possibles TRUE/FALSE or 0/1
--limit | Limitar els resultats a un número determinat
--offset | Punt d'inici del límit

## Arguments disponibles
Argument | Detalls
---------|-------------
yaml-left | Fitxer YAML utilitzat com va base per la comparació
yaml-right | Fitxer YAML utilitzat per trobar diferències amb el fitxer YAML base
