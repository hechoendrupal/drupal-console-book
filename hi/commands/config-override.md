# config:override
व्यवस्था निधि को सक्रिय डायरेक्टरी में चढ़ा दें।

**प्रयोग:**
```
$ drupal config:override [arguments]
```

## उपलब्ध तर्कों
तर्क | विवरण
---------|-------------
config-name | व्यवस्था का नाम।
key | कुंजी
value | निधि

## उदाहरण
* "flood" मॉड्यूल संपर्क 10 का मूल्य निर्धारित किया है।
```
$ drupal config:override contact.settings flood.limit 10
```
