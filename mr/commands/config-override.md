# config:override
सक्रिय कॉन्फिगरेशनमध्ये कॉन्फिगर मूल्य अधिशून्य करा.

**वापर:**
```
drupal config:override [arguments]
co
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
name | कॉन्फिगरेशन नाव.
key | की
value | मूल्य

## उदाहरणे
* संपर्क मंडळाची पूर मर्यादा 10 वर सेट करा.
```
drupal config:override contact.settings flood.limit 10
```
