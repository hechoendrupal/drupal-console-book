# generate:controller
उत्पन्न करा आणि कंट्रोलर नोंदवा

**वापर:**
```
drupal generate:controller [options]
gcon
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | कंट्रोलर वर्ग नाव
--routes | routes, हे [title, method, path] असलेले अॅरे असले पाहिजेत
--services | कंटेनर मधून सेवा भरा.
--test | चाचणी वर्ग उत्पन्न करा

## उदाहरणे
* मॉड्युल नाव, वर्ग नाव व त्याचे रूट निर्दिष्ट करणारा कंट्रोलर उत्पन्न करा.
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
