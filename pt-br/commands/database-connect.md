# database:connect
Iniciar um cliente de banco de dados se ele está disponível

**application.gitbook.messages.usage:**
```
drupal database:connect [arguments]
dbco
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Senha do banco de dados em settings.php

## application.gitbook.messages.examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
