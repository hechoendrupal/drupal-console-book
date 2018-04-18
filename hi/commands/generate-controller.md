# generate:controller
एक कंट्रोलर को उत्पन्न और पंजीकृत करें

**Usage:**
```
drupal generate:controller [options]
gcon
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | कंट्रोलर क्लास का नाम
--routes | मार्गों युक्त एक सरणी होना चाहिए [शीर्षक, विधि, पथ]
--services | सर्विसेज़ को container से लोड करें।
--test | एक परिक्षण क्लास उत्पन्न करें

## Examples
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
