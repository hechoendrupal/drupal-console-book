# cron:execute
क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें

**Usage:**
```
drupal cron:execute [arguments]
croe
cre
```

## Available arguments
Argument | Details
---------|-------------
module | मोड्यूल का नाम।

## Examples
* Execute the cron globally
```
drupal cron:execute
```
* Execute the cron on the specified module
```
drupal cron:execute \
  <module>
```
