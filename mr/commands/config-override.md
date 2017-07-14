# config:override
सक्रिय कॉन्फिगरेशनमध्ये कॉन्फिगर मूल्य अधिशून्य करा.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | कॉन्फिगरेशन नाव.
key | की
value | मूल्य

## application.gitbook.messages.examples
* संपर्क मंडळाची पूर मर्यादा 10 वर सेट करा.
```
drupal config:override contact.settings flood.limit 10
```
