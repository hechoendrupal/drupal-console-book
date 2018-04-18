# module:download
अर्ज मॉड्यूल किंवा मॉड्यूल डाउनलोड करा.

**वापर:**
```
drupal module:download [arguments] [options]
mod
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--path | Contrib प्रकल्प मार्ग.
--latest | सर्वात अलीकडील आवृत्ती डाउनलोड करण्यासाठी डीफॉल्ट.
--composer | Composer वापरून मॉड्यूल डाउनलोड करा.
--unstable | Module unstable

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
module | सक्षम केलेल्या मोड्यूल किंवा मॉड्यूल्सना स्पेसद्वारे विभक्त व्हायला हवे.

## उदाहरणे
* डाऊनलोड मॉड्युल मॉड्यूलचे नाव आणि त्याचे पथ.
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
