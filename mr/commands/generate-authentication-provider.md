# generate:authentication:provider
एक प्रमाणीकरण प्रदाता उत्पन्न करा.

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्रमाणीकरण प्रदाता वर्ग.
--provider-id | प्रदाता आयडी.

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
