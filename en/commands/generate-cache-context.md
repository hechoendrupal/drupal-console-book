# generate:cache:context
Generate a cache context

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:cache:context [options]
gcc
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--cache-context | Enter the cache context name
--class | Cache context class name
--services | Load services from the container.

## commands.generate.doc.gitbook.messages.examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
