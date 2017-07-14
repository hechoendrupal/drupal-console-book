# config:diff
आउटपुट विन्यास आइटम है कि एक डायरेक्टरी के साथ तुलना में सक्रिय कॉन्फ़िगरेशन में अलग हैं।

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | रिवर्स में परिवर्तन देखें (i.e सक्रिय कॉन्फ़िगरेशन के लिए एक डिफ़्फ निर्देशिका)।

## Available arguments
Argument | Details
---------|-------------
directory | diff के लिए डायरेक्टरी के विरुद्ध। Drupal कॉन्फिग डायरेक्ट्रीज से चुनें, यदि छोड़ा जाता है।

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
