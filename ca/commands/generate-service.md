# generate:service
Generar un servei

**Ús:**
```
drupal generate:service [options]
gs
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--name | Nom del servei
--class | Nom de la classe
--interface | Interfície
--interface-name | Interface name
--services | Carregar serveis des del contenidor.
--path-service | Path

## Exemples
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
