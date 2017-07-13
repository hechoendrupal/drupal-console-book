# config:diff
आउटपुट विन्यास आइटम है कि एक डायरेक्टरी के साथ तुलना में सक्रिय कॉन्फ़िगरेशन में अलग हैं।

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:diff [arguments] [options]
$ cdi  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--reverse | रिवर्स में परिवर्तन देखें (i.e सक्रिय कॉन्फ़िगरेशन के लिए एक डिफ़्फ निर्देशिका)।

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
directory | diff के लिए डायरेक्टरी के विरुद्ध। Drupal कॉन्फिग डायरेक्ट्रीज से चुनें, यदि छोड़ा जाता है।

## commands.generate.doc.gitbook.messages.examples
* Provide a config directory
```
$ drupal config:diff ../config/path
```
