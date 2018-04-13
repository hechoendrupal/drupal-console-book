# generate:service
Generate service

**Usage:**
```
drupal generate:service [options]
gs
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--name | Service name
--class | Class name
--interface | Interface
--interface-name | Interface name
--services | Load services from the container.
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
