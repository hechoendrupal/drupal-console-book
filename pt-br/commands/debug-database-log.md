# debug:database:log
Exibir eventos de log atuais do aplicativo

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
--limit | Limite os resultados a um número específico
--offset | Ponto de partida de um limite
--yml | Print in a yml style

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
event-id | DBLog evento ID
