# generate:service
सेवा उत्पन्न करा

**वापर:**
```
drupal generate:service [options]
gs
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--name | सेवेचे नाव
--class | वर्ग नाव
--interface | इंटरफेस
--interface-name | Interface name
--services | कंटेनर मधून सेवा भरा.
--path-service | Path

## उदाहरणे
* मॉड्यूल नाव, सेवा नाव, वर्ग आणि त्याचे पथ निर्देशीत इंटरफेसशिवाय सेवा उत्पन्न करा.
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --path-service="/modules/custom/modulename/src/"
```
* मॉड्युलचे नाव, सेवा नाव, वर्ग, इंटरफेस नाव आणि त्याचे पथ निर्दिष्ट करणार्या इंटरफेससह सेवा उत्पन्न करा.
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --interface  \
  --interface-name="InterfaceName"  \
  --path-service="/modules/custom/modulename/src/"
```
