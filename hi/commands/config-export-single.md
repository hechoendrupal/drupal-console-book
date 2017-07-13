# config:export:single
एक कॉन्फिग को yml फाइल के जैसे निर्यात करें।

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:single [options]
$ ces  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--name | commands.config.export.single.options.name
--directory | कॉन्फ़िगरेशन उत्पादन को सेव करने के लिए एक्सपोर्ट डायरेक्टरी को परिभाषित करें।
--module | मोड्यूल का नाम।
--include-dependencies | कॉन्फ़िगरेशन का निर्भरता के रूप में अच्छी तरह से एक्सपोर्ट करे।
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## commands.generate.doc.gitbook.messages.examples
* Provide config settings name to be exported
```
$ drupal config:export:single \
  --name=config.settings.name
```
* if uuid and/or config hashes will be removed.
```
$ drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash

```
