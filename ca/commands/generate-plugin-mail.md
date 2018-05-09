# generate:plugin:mail
Generate a plugin mail

**Ús:**
```
drupal generate:plugin:mail [options]
gpm
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--services | Carregar serveis des del contenidor.

## Exemples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
