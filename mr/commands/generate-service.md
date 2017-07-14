# generate:service
सेवा उत्पन्न करा

**Usage:**
```
drupal generate:service [options]
gs
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--name | commands.generate.service.options.name
--class | वर्ग नाव
--interface | commands.common.service.options.interface
--interface-name | commands.common.service.options.interface-name
--services | कंटेनर मधून सेवा भरा.
--path-service | मार्ग

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
