# debug:database:log
Afișează evenimentele curente, de intrare în jurnal, pentru aplicație

**application.gitbook.messages.usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limitați rezultatele la un anumit număr
--offset | Punctul de început al unei limite
--yml | Print in a yml style

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | ID-ul evenimentului DBLog
