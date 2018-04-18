# generate:service
सर्विस उत्पन्न करें

**Usage:**
```
drupal generate:service [options]
gs
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--name | सर्विस का नाम
--class | क्लास का नाम
--interface | इंटरफ़ेस
--interface-name | Interface name
--services | सर्विसेज़ को container से लोड करें।
--path-service | Path

## Examples
* Generate a services without interface specifying the module name, the service name, the class and its path
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --path-service="/modules/custom/modulename/src/"
```
* Generate a services with interface specifying the module name, the service name, the class, the interface name and its path
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --interface  \
  --interface-name="InterfaceName"  \
  --path-service="/modules/custom/modulename/src/"
```
