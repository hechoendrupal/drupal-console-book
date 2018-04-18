# debug:plugin
Mostra todos os tipos de plugins, instâncias de um tipo específico de plugin ou a definição para um plugin específico.

**Utilização:**
```
drupal debug:plugin [arguments]
dpl
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
type | Tipo de plugin
id | Plugin ID

## Exemplos
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
