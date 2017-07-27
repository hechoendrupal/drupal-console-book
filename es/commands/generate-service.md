# generate:service
Genera un servicio

**Uso:**
```
drupal generate:service [options]
gs
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--name | commands.generate.service.options.name
--class | Nombre de la clase
--interface | commands.common.service.options.interface
--interface-name | commands.common.service.options.interface-name
--services | Cargar servicios desde el contenedor.
--path-service | Ruta

## Ejemplos
* Generar un servicio sin interfaz especificando el nombre del módulo, el nombre del servicio, la clase y el path del servicio
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --path-service="/modules/custom/modulename/src/"
```
* Generar un servicio con interfaz especificando el nombre del módulo, el nombre del servicio, la clase, el nombre de interfaz y su ruta
```
drupal generate:service  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultService"  \
  --interface  \
  --interface-name="InterfaceName"  \
  --path-service="/modules/custom/modulename/src/"
```
