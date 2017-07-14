# debug:config
चालू संरचना दाखवा.

**Usage:**
```
drupal debug:config [arguments]
dc
```

## Available arguments
Argument | Details
---------|-------------
name | संरचने नाव.

## Examples
* सर्व कॉन्फिगरेशन ऑब्जेक्ट नावांची यादी करा.
```
drupal config:debug
```
* सिस्टम साइट कॉन्फिगरेशन मूल्य प्रदर्शित करा.
```
drupal config:debug system.site
```
* सर्व सिस्टम कॉन्फिगरेशन नावांची यादी करा.
```
drupal config:debug | grep system
```
