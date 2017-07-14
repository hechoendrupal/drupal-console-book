# debug:module
अनुप्रयोगासाठी उपलब्ध असलेले वर्तमान मॉड्यूल प्रदर्शित करा.

**application.gitbook.messages.usage:**
```
drupal debug:module [arguments] [options]
dm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--status | मॉड्यूल स्थिती [सक्षम | अक्षम]
--type | मॉड्यूल प्रकार [कोर | नो-कोर]

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | मॉड्यूल नाव

## application.gitbook.messages.examples
* सर्व स्थापित मॉड्यूल प्रदर्शित करा
```
drupal mod --status=installed
```
* सर्व स्थापित आणि कोणतेही कोर मॉड्यूल प्रदर्शित करा
```
drupal mod --status=installed --type=no-core
```
