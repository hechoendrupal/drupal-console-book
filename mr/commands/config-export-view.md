# config:export:view
अन्य वेबसाइटवर पुनर्वापरासाठी प्रदान केलेल्या मॉड्यूलमध्ये YAML स्वरूपात एक दृश्य निर्यात करा.

**वापर:**
```
drupal config:export:view [arguments] [options]
cev
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--optional-config | आपल्या मॉड्यूलमध्ये एक वैकल्पिक YAML कॉन्फिगरेशन म्हणून दृश्य निर्यात करा.
--include-module-dependencies | मॉड्यूल माहिती YAML फाइलमध्ये मॉड्यूल अवलंबन समाविष्ट करा.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
view-id | दृश्य आयडी

## उदाहरणे
* दृश्य आयडी द्या.
```
drupal config:export:view viewid
```
* आपण परस्परसंवादी मूल्ये जसे पॅरामीटर प्रदान करू शकता.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
