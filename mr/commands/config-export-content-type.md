# config:export:content:type
विशिष्ट सामग्री प्रकार आणि त्यांचे फील्ड निर्यात करा.

**वापर:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--optional-config | एक पर्यायी YAML संरचना म्हणून मॉड्यूल मध्ये कॉन्तेंत ट्यीप  निर्यात करा.
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
content-type | सामुग्री प्रकार निर्यात करणे.

## उदाहरणे
* एक सामग्री प्रकार आणि मॉड्यूल नाव प्रदान करा.
```
drupal config:export:content:type page \
  --module="demo"
```
* आपण इच्छित असल्यास निर्यात सामग्री प्रकार पर्यायी कॉन्फिग प्रदान करा.
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
