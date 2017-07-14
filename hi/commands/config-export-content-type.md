# config:export:content:type
किसी विशेष कंटेंट टाइप और उनके खानो का एक्सपोर्ट करें।

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | ऐच्छिक YAML कॉन्फिग स्वरूप मॉड्यूल में कंटेंट टाइप निर्यात करें

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | कंटेंट टाइप एक्सपोर्ट किए जाये

## application.gitbook.messages.examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
