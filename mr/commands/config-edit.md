# config:edit
निवडलेले संरचना संपादित करा.

**वापर:**
```
drupal config:edit [arguments]
ced
cdit
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
config-name | संरचने नाव.
editor | संपादक

## उदाहरणे
* "Vim" (डीफॉल्ट संपादक) सह सिस्टम क्रोन कॉन्फिगरेशन संपादित करा.
```
drupal config:edit system.cron
```
* "gedit" सह सिस्टम क्रोन कॉन्फिगरेशन संपादित करा.
```
drupal config:edit system.cron gedit
```
