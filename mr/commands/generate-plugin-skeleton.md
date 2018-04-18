# generate:plugin:skeleton
त्या प्लगिनसाठी स्केप्लेट प्लगइनची अंमलबजावणी उत्पन्न करा Drupal Console मध्ये विशिष्ट जनरेटर नाही.

**वापर:**
```
drupal generate:plugin:skeleton [options]
gps
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--plugin-id | प्लगइन आयडी.
--class | प्लगइन वर्ग नाव.
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्यूल नाव, प्लगिन आयडी आणि क्लास निर्दिष्ट करणारा एक प्लगइन स्केलेमेंट उत्पन्न करा.
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
