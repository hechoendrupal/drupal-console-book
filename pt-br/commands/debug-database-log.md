# debug:database:log
Exibir eventos de log atuais do aplicativo

**Utilização:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | Limite os resultados a um número específico
--offset | Ponto de partida de um limite
--yml | Print in a yml style

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
event-id | DBLog evento ID

## Exemplos
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
