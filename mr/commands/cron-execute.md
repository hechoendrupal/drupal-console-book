# cron:execute
क्रॉन लागू करणारे काही विशेष मोड्यूल चालावा अथवा सर्व क्रॉन चालवा.

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | मॉड्यूलचे नाव.

## Examples
* जागतिक पातळीवर क्रोन चालवा.
```
drupal cron:execute
```
* निर्दिष्ट केलेल्या मॉड्यूलवर क्रोन कार्यान्वित करा.
```
drupal cron:execute \
  <module>
```
