# config:override
व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | कुंजी
value | निधि

## Examples
* "flood" मॉड्यूल संपर्क 10 का मूल्य निर्धारित किया है।
```
drupal config:override contact.settings flood.limit 10
```
