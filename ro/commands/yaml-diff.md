# yaml:diff
Compară două fişiere YAML pentru a determina diferenţele dintre acestea.

**Folosire:**
```
$ drupal yaml:diff [arguments] [options]
$ yd  
```

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--stats | Afișează statistici cu privire la compararea fișierelor YAML
--negate | Definiți modul de diferență sau de comparație egală, valori posibile TRUE/FALSE sau 0/1
--limit | Limitează rezultatele la un anumit număr
--offset | Punctul de început al unei limite

## Argumente disponibile
Argument | Detalii
---------|-------------
yaml-left | Fişierul YAML folosit ca bază pentru comparare.
yaml-right | Fişierul YAML folosit pentru a determina lipsurile şi diferenţele cu fişierul de bază.
