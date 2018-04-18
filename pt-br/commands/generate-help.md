# generate:help
Generate an implementation of hook_help()

**Utilização:**
```
drupal generate:help [options]
gh
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--description | commands.generate.help.options.description

## Exemplos
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
