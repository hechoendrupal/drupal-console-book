# config:diff
एक निर्देशिका तुलनेत सक्रिय संरचना भिन्न आहेत की आउटपुट कॉन्फिगरेशन आयटम.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | उलट मध्ये बदल पहा (दुसऱ्या शब्दात सांगायचे म्हणजे सक्रिय कॉन्फिगरेशन निर्देशिकाचे फरक).

## Available arguments
Argument | Details
---------|-------------
directory | विरुद्ध फरक डिरेक्टरी. वगळल्यास, Drupal कॉनफिग संचयीका निवडा.

## Examples
* एक संरचना निर्देशिका द्या.
```
drupal config:diff ../config/path
```
