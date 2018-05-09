# cron:execute
Executar l'implementació de cron per mòdul o executar-los tots

**Ús:**
```
drupal cron:execute [arguments]
croe
cre
```

## Arguments disponibles
Argument | Detalls
---------|-------------
module | Nom del mòdul.

## Exemples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
