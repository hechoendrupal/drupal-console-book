# generate:service
Criar serviço

**Utilização:**
```
drupal generate:service [options]
gs
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--name | Nome do serviço
--class | Nome da classe
--interface | Interface
--interface-name | Interface name
--services | Carrega serviços do container.
--path-service | Path

## Exemplos
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
