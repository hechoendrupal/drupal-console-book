# config:override
सक्रिय कॉन्फिगरेशनमध्ये कॉन्फिगर मूल्य अधिशून्य करा.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | कॉन्फिगरेशन नाव.
key | की
value | मूल्य

## Examples
* संपर्क मंडळाची पूर मर्यादा 10 वर सेट करा.
```
drupal config:override contact.settings flood.limit 10
```
