# generate:plugin:rulesaction
Genera un plugin de acción de rules

**Uso:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de clase del plugin
--label | Etiqueta del plugin
--plugin-id | ID del plugin
--type | Tipo de acción (usuario o nodo)
--category | Categoría del plugin
--context | Contexto del plugin

## Ejemplos
* Generar un plugin de acción de rule de usuario especificando el nombre del módulo, la clase, su etiqueta, el id de plugin, el tipo,  su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, su etiqueta, el id de plugin, el tipo, la categoría y su contexto
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="user"  \
  --category="default_action"  \
  --context="default_action"
```
* Generar un plugin de acción de rule de nodo especificando el nombre del módulo, la clase, su etiqueta, el id de plugin, el tipo, la categoría y su contexto
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="node"  \
  --category="default_action" \
  --context="default_action"
```
