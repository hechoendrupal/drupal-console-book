# debug:database:log
Az alkalmazás aktuális naplóeseményeinek megjelenítése

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
--limit | Egy adott számra korlátozza a találatok számát
--offset | Egy korlát kezdőpontja
--yml | Print in a yml style

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | DBLog eseményazonosító
