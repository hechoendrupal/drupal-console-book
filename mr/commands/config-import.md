# config:import
वर्तमान अनुप्रयोगावरील कॉन्फिगरेशन आयात करा.

**वापर:**
```
drupal config:import [options]
ci
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--file | आयात करण्यासाठी कॉन्फिगरेशनच्या संग्रहण फाईलचा मार्ग.
--directory | आयात करण्यासाठी कॉन्फिगरेशनच्या निर्देशिकेत मार्ग.
--remove-files | सिंक्रोनाइझेशननंतर फायली काढा.
--skip-uuid | commands.config.import.options.skip-uuid

## उदाहरणे
* संरचना फाइल पुरवा.
```
drupal config:import \
  --file=/path/to/config/file
```
* संरचना निर्देशिका द्या.
```
drupal config:import  \
  --directory=/path/to/config/dir
```
