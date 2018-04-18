# generate:authentication:provider
एक प्रमाणीकरण प्रदाता उत्पन्न करा.

**वापर:**
```
drupal generate:authentication:provider [options]
gap
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्रमाणीकरण प्रदाता वर्ग.
--provider-id | प्रदाता आयडी.

## उदाहरणे
* मॉड्यूल, वर्ग आणि प्रदाता आयडी निर्दिष्ट करणारा प्रमाणीकरण प्रदाता उत्पन्न करा.
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
