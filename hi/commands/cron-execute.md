# cron:execute
क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें

**application.gitbook.messages.usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | मोड्यूल का नाम।

## application.gitbook.messages.examples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
