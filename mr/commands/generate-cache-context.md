# generate:cache:context
कॅशे संदर्भ उत्पन्न करा.

**Usage:**
```
drupal generate:cache:context [options]
gcc
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--cache-context | कॅशे संदर्भ नाव प्रविष्ट करा.
--class | कॅशे संदर्भ क्लास नाव.
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
