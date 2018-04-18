# config:export:single
Yml फाइल म्हणून एकच कॉन्फिगरेशन निर्यात करा.

**वापर:**
```
drupal config:export:single [options]
ces
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | मॉड्यूलचे नाव.
--include-dependencies | तसेच कॉन्फिगरेशनची अवलंबन निर्यात करा.
--optional | आपल्या मॉड्यूलमध्ये वैकल्पिक YAML कॉन्फिगरेशन म्हणून निर्यात एक्सपोर्ट करा.
--remove-uuid | सेट केल्यास, uuid कीशिवाय कॉन्फिगरेशन निर्यात केले जाईल.
--remove-config-hash | सेट केल्यास, डीफॉल्ट साइट हॅश कीशिवाय कॉन्फिगरेशन निर्यात केले जाईल.

## उदाहरणे
* निर्यात करण्याकरिता कॉन्फिगरेशन संरचना नाव प्रदान करा.
```
drupal config:export:single \
  --name=config.settings.name
```
* जर uuid आणि / किंवा कॉन्फिग हॅश काढून टाकले जातील.
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```
