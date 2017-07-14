# debug:module
अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | मोड्यूल स्थिति [चालू है | बंद है]
--type | मोड्यूल प्रकार [मूल|मूल नही]

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | Module name

## application.gitbook.messages.examples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
