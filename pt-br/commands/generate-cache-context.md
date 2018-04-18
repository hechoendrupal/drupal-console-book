# generate:cache:context
Generate a cache context

**Utilização:**
```
drupal generate:cache:context [options]
gcc
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--cache-context | The cache context name
--class | Cache context class name
--services | Carrega serviços do container.

## Exemplos
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
