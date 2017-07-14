# generate:plugin:mail
Génère un plugin de courriel

**Usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## Available options
Option | Details
-------|-------------
--module | Le nom du module.
--class | Nom de la classe de plugin
--label | Label du plugin
--plugin-id | Id du plugin
--services | Charger des services depuis le conteneur.

## Examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
