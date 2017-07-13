# debug:database:log
Afișează evenimentele curente, de intrare în jurnal, pentru aplicație

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:database:log [arguments] [options]
$ dbb  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limitați rezultatele la un anumit număr
--offset | Punctul de început al unei limite
--yml | Print in a yml style

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
event-id | ID-ul evenimentului DBLog
