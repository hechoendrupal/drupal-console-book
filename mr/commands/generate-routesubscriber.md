# generate:routesubscriber
एक RouteSubscriber उत्पन्न करा.

**वापर:**
```
drupal generate:routesubscriber [options]
gr
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--name | सेवेचे नाव
--class | वर्ग नाव

## उदाहरणे
* मॉड्यूल नाव, मार्ग नाव आणि त्याचे वर्ग निर्दिष्ट करणारा मार्ग ग्राहक उत्पन्न करा.
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
