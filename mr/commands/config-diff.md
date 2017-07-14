# config:diff
एक निर्देशिका तुलनेत सक्रिय संरचना भिन्न आहेत की आउटपुट कॉन्फिगरेशन आयटम.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | उलट मध्ये बदल पहा (दुसऱ्या शब्दात सांगायचे म्हणजे सक्रिय कॉन्फिगरेशन निर्देशिकाचे फरक).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | विरुद्ध फरक डिरेक्टरी. वगळल्यास, Drupal कॉनफिग संचयीका निवडा.

## application.gitbook.messages.examples
* एक संरचना निर्देशिका द्या.
```
drupal config:diff ../config/path
```
