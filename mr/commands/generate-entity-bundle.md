# generate:entity:bundle
नवीन सामग्री प्रकार उत्पन्न करा (नोड / एंटिटीचे बंडल)

**वापर:**
```
drupal generate:entity:bundle [options]
geb
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--bundle-name | सामग्रीचे प्रकारचे मशीन नाव.
--bundle-title | सामग्री प्रकारचे मानवी-वाचनीय नाव.

## उदाहरणे
* मॉड्यूल, बंडल नाव आणि त्याचे शीर्षक निर्दिष्ट बंडल अस्तित्व उत्पन्न करा.
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
