# generate:plugin:mail
Generate a plugin mail

**Utilização:**
```
drupal generate:plugin:mail [options]
gpm
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--services | Carrega serviços do container.

## Exemplos
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
