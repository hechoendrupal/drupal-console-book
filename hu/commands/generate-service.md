# generate:service
Szolgáltatás létrehozása

**Usage:**
```
drupal generate:service [options]
gs
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--name | Szolgáltatásnév
--class | Osztálynév
--interface | Interfész
--interface-name | Interface name
--services | Szolgáltatások betöltése a tárolóból.
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
