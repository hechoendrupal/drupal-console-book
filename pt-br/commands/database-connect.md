# database:connect
Iniciar um cliente de banco de dados se ele está disponível

**Utilização:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
database | Senha do banco de dados em settings.php

## Exemplos
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
