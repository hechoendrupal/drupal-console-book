# generate:cache:context
Generate a cache context

**application.gitbook.messages.usage:**
```
drupal generate:cache:context [options]
gcc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--cache-context | Enter the cache context name
--class | Cache context class name
--services | Load services from the container.

## application.gitbook.messages.examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
