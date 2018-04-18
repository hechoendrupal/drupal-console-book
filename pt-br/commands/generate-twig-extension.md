# generate:twig:extension
Generate a Twig extension.

**Utilização:**
```
drupal generate:twig:extension [options]
gte
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--name | Twig Extension name
--class | Class name
--services | Carrega serviços do container.

## Exemplos
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
