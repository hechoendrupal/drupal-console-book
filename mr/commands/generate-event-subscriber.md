# generate:event:subscriber
एक कार्यक्रम ग्राहक उत्पन्न करा.

**वापर:**
```
drupal generate:event:subscriber [options]
ges
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--name | Service name
--class | Class name
--events | कंटेनर मधून इव्हेंट्स भरा.
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्यूल नाव, त्याचे नाव, वर्ग आणि सदस्यता घेण्यासाठी इव्हेंट्स निर्दिष्ट करणारा एक इव्हेंट सब्सक्राइबर उत्पन्न करा.
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
