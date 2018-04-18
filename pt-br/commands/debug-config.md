# debug:config
Exibe a configuração atual.

**Utilização:**
```
drupal debug:config [arguments] [options]
dc
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--show-overridden | Show overridden configurations.

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
name | Nome da configuração.

## Exemplos
* List all configuration object names.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* List all system configuration names.
```
drupal config:debug | grep system
```
* List all configuration including overridden values.
```
drupal debug:config --show-overridden
```
