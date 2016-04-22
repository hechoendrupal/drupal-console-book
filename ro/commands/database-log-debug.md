# database:log:debug
Afișează evenimentele curente, de intrare în jurnal, pentru aplicație

**Folosire:**
```
$ drupal database:log:debug [arguments] [options]
```

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--type | Filtrați evenimentele după un anumit tip
--severity | Filtrați evenimentele după un anumit nivel de severitate
--user-id | Filtrați evenimentele după un anumit id de utilizator
--reverse | Reverse the order of events
--limit | Limitați rezultatele la un anumit număr
--offset | Punctul de început al unei limite

## Argumente disponibile
Argument | Detalii
---------|-------------
event-id | ID-ul evenimentului DBLog
