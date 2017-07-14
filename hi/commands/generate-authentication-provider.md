# generate:authentication:provider
प्रमाणन प्रदाता उत्पन्न करें

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | ऑथेंटिकेशन प्रोवाइडर क्लास
--provider-id | प्रदाता क्रमांक

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
