# config:export:content:type
किसी विशेष कंटेंट टाइप और उनके खानो का एक्सपोर्ट करें।

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:content:type [arguments] [options]
$ cect  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | ऐच्छिक YAML कॉन्फिग स्वरूप मॉड्यूल में कंटेंट टाइप निर्यात करें

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-type | कंटेंट टाइप एक्सपोर्ट किए जाये

## commands.generate.doc.gitbook.messages.examples
* Provide a content type  and module name
```
$ drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
$ drupal config:export:content:type page \
  --module="demo" \
  --optional-config 

```
