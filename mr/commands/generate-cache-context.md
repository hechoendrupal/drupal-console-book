# generate:cache:context
कॅशे संदर्भ उत्पन्न करा.

**वापर:**
```
drupal generate:cache:context [options]
gcc
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--cache-context | The cache context name
--class | Cache context class name
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्यूल, संदर्भ नाव आणि त्याचे वर्ग निर्दिष्ट करणार्या संदर्भासाठी कॅशे उत्पन्न करा.
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
