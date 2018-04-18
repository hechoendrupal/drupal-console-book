# generate:entity:config
नवीन कॉन्फिग एंटिटी उत्पन्न करा.

**वापर:**
```
drupal generate:entity:config [options]
gec
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--entity-class | कॉन्फिग एंटिटी वर्ग.
--entity-name | संरचना अस्तित्व नाव.
--base-path | संरचना अस्तित्व मार्ग साठी बेस-पथ.
--label | लेबल
--bundle-of | सामग्री एंटिटीसाठी बंडल म्हणून कार्य.

## उदाहरणे
* मॉड्यूल, अस्तित्व श्रेणी, अस्तित्व नाव, त्याचे पथ आणि लेबल निर्दिष्ट करणारी संरचना संस्था उत्पन्न करा.
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
