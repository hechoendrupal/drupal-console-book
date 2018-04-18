# state:override
एखाद्या स्थिती की वर अधिशून्य करा.

**वापर:**
```
drupal state:override [arguments]
sto
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
key | अधिलिखित करण्यासाठी स्थिती की.
value | सेट करण्यासाठी स्थिती मूल्य.

## उदाहरणे
* स्थिती नाव अधोरेखीत करते आणि स्थिती नाव आणि नवीन मूल्य निर्दिष्ट करते.
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
