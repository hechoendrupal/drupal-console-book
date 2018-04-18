# debug:container
Exibe serviços atuais para um aplicativo.

**Utilização:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--parameters | Service name.
--tag | Service tag 

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Exemplos
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
