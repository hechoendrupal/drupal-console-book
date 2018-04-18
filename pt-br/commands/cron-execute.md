# cron:execute
Executar cron de um módulo específico ou todos para executar todas as implementações

**Utilização:**
```
drupal cron:execute [arguments]
croe
cre
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
module | O nome do módulo.

## Exemplos
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
