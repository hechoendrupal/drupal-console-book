# config:override
व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | कुंजी
value | निधि

## application.gitbook.messages.examples
* "flood" मॉड्यूल संपर्क 10 का मूल्य निर्धारित किया है।
```
drupal config:override contact.settings flood.limit 10
```
