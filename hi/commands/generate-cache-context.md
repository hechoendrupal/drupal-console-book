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
--module | मोड्यूल का नाम।
--cache-context | The cache context name
--class | Cache context class name
--services | सर्विसेज़ को container से लोड करें।

## Examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
