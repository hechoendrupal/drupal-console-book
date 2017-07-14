# debug:module
अनुप्रयोगासाठी उपलब्ध असलेले वर्तमान मॉड्यूल प्रदर्शित करा.

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | मॉड्यूल स्थिती [सक्षम | अक्षम]
--type | मॉड्यूल प्रकार [कोर | नो-कोर]

## Available arguments
Argument | Details
---------|-------------
module | मॉड्यूल नाव

## Examples
* सर्व स्थापित मॉड्यूल प्रदर्शित करा
```
drupal mod --status=installed
```
* सर्व स्थापित आणि कोणतेही कोर मॉड्यूल प्रदर्शित करा
```
drupal mod --status=installed --type=no-core
```
