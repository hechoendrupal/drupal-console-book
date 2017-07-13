# database:connect
Iniciar um cliente de banco de dados se ele está disponível

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal database:connect [arguments]
$ dbco  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
database | Senha do banco de dados em settings.php

## commands.generate.doc.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
$ drupal database:connect \
  <database>

```
