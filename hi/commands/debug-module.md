# debug:module
अनुप्रयोग के उपलब्ध मोड्यूलो को दिखाएँ

**Usage:**
```
drupal debug:module [arguments] [options]
dm
```

## Available options
Option | Details
-------|-------------
--status | मोड्यूल स्थिति [चालू है | बंद है]
--type | मोड्यूल प्रकार [मूल|मूल नही]

## Available arguments
Argument | Details
---------|-------------
module | Module name

## Examples
* Display all installed modules
```
drupal mod --status=installed
```
* Display all installed and no core modules
```
drupal mod --status=installed --type=no-core
```
