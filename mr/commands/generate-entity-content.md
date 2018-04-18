# generate:entity:content
एक नवीन सामग्री एंटिटी उत्पन्न करा.

**वापर:**
```
drupal generate:entity:content [options]
geco
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--entity-class | सामग्री अस्तित्व श्रेणी.
--entity-name | सामग्री अस्तित्व नाव.
--base-path | सामग्री अस्तित्व मार्गांसाठीचा बेथ-पथ.
--label | लेबल
--has-bundles | अस्तित्वचे समूह आहे.
--is-translatable | सामग्री अस्तित्व भाषांतरयोग्य.
--revisionable | commands.generate.entity.content.options.revisionable

## उदाहरणे
* मॉड्यूल, घटक वर्ग, अस्तित्व नाव, त्याचे पथ आणि लेबल निर्दिष्ट करणारी एक सामग्री अस्तित्व उत्पन्न करा.
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* मॉड्यूल, एंटिटी क्लास, एंटिटीचे नाव, त्याचे पथ आणि लेबल निर्दिष्ट करणारे भाषांतरयोग्य आणि पुनरावर्तनीय सामग्री अस्तित्व उत्पन्न करा.
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
