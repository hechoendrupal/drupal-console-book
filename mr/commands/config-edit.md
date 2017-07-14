# config:edit
निवडलेले संरचना संपादित करा.

**Usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## Available arguments
Argument | Details
---------|-------------
config-name | संरचने नाव.
editor | संपादक

## Examples
* "Vim" (डीफॉल्ट संपादक) सह सिस्टम क्रोन कॉन्फिगरेशन संपादित करा.
```
drupal config:edit system.cron
```
* "gedit" सह सिस्टम क्रोन कॉन्फिगरेशन संपादित करा.
```
drupal config:edit system.cron gedit
```
