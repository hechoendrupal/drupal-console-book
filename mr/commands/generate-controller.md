# generate:controller
उत्पन्न करा आणि कंट्रोलर नोंदवा

**Usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | कंट्रोलर वर्ग नाव
--routes | routes, हे [title, method, path] असलेले अॅरे असले पाहिजेत
--services | कंटेनर मधून सेवा भरा.
--test | चाचणी वर्ग उत्पन्न करा

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
