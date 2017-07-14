# generate:service
Generate service

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:service [options]
gs
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--name | commands.generate.service.options.name
--class | Class name
--interface | commands.common.service.options.interface
--interface-name | commands.common.service.options.interface-name
--services | Load services from the container.
--path-service | Path

## commands.generate.doc.gitbook.messages.examples
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
