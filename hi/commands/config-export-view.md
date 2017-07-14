# config:export:view
एक व्यू को YAML संरूप में एक्सपोर्ट करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | व्यू को ऐच्छिक YAML कॉन्फिग स्वरूप अपने मॉड्यूल में निर्यात करें
--include-module-dependencies | व्यू मॉड्यूल निर्भरता को मॉड्यूल info YAML फाइल में सम्मिलित करें

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | व्यू आईडी

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
