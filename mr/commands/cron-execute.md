# cron:execute
क्रॉन लागू करणारे काही विशेष मोड्यूल चालावा अथवा सर्व क्रॉन चालवा.

**application.gitbook.messages.usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | मॉड्यूलचे नाव.

## application.gitbook.messages.examples
* जागतिक पातळीवर क्रोन चालवा.
```
drupal cron:execute
```
* निर्दिष्ट केलेल्या मॉड्यूलवर क्रोन कार्यान्वित करा.
```
drupal cron:execute \
  <module>
```
