# debug:config
चालू संरचना दाखवा.

**वापर:**
```
drupal debug:config [arguments] [options]
dc
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--show-overridden | Show overridden configurations.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
name | संरचने नाव.

## उदाहरणे
* सर्व कॉन्फिगरेशन ऑब्जेक्ट नावांची यादी करा.
```
drupal config:debug
```
* सिस्टम साइट कॉन्फिगरेशन मूल्य प्रदर्शित करा.
```
drupal config:debug system.site
```
* सर्व सिस्टम कॉन्फिगरेशन नावांची यादी करा.
```
drupal config:debug | grep system
```
* List all configuration including overridden values.
```
drupal debug:config --show-overridden
```
