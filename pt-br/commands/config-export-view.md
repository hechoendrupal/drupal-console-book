# config:export:view
Exportar uma view no formato YAML em um módulo, para reutilizar em outro website.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar a view como uma configuração YAML opcional em seu módulo
--include-module-dependencies | Incluir as dependências do módulo em um arquivo YAML de informação do módulo

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | ID da view

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
