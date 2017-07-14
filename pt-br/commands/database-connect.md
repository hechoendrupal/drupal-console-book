# database:connect
Iniciar um cliente de banco de dados se ele está disponível

**Usage:**
```
drupal database:connect [arguments]
dbco
```

## Available arguments
Argument | Details
---------|-------------
database | Senha do banco de dados em settings.php

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
