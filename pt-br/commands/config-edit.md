# config:edit
Edite a configuração selecionada.

**Utilização:**
```
drupal config:edit [arguments]
ced
cdit
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
config-name | Nome da configuração.
editor | Editor.

## Exemplos
* Edite configurações do sistema cron com "vim" (editor padrão).
```
drupal config:edit system.cron
```
* Edite configurações do sistema cron com "gedit".
```
drupal config:edit system.cron gedit
```
