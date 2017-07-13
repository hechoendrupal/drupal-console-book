# cron:execute
क्रॉन लागू करने वाले किसी विशेष मोड्यूल को चलायें या सारे क्रॉन चलायें

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | मोड्यूल का नाम।

## commands.generate.doc.gitbook.messages.examples
* Execute the cron globally
```
$ drupal cron:execute

```
* Execute the cron on the specified module
```
$ drupal cron:execute \
  <module>

```
