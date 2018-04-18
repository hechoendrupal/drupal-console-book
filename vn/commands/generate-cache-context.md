# generate:cache:context
Generate a cache context

**Usage:**
```
drupal generate:cache:context [options]
gcc
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--cache-context | The cache context name
--class | Cache context class name
--services | Nạp các dịch vụ từ container.

## Examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
