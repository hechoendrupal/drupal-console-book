# generate:plugin:views:field
Generate a custom plugin view field.

**Utilização:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Views plugin field class name
--title | Views plugin field title
--description | Views plugin field description

## Exemplos
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
