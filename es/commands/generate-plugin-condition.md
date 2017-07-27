# generate:plugin:condition
Genera un plugin de condición.

**Uso:**
```
drupal generate:plugin:condition [options]
gpco
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase para el plugin de condición
--label | Etiqueta del plugin de condición
--plugin-id | ID del plugin de condición
--context-definition-id | ID de definición de contexto
--context-definition-label | Etiqueta de la definición de contexto
--context-definition-required | Una definición de contexto es obligatoria (TRUE/FALSE)

## Ejemplos
* Generar un plugin de condición para un tipo de entidad nodo especificando el nombre del módulo, la clase, la etiqueta su id y la definición de contexto
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:node"  \
  --context-definition-label="node"  \
  --context-definition-required
```
* Generar un plugin de condición para idioma especificando el nombre del módulo, la clase, la etiqueta su id y la definición de contexto
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="language"  \
  --context-definition-label="Language"  \
  --context-definition-required
```
* Generar un plugin de condición para configuración de rol especificando el nombre del módulo, la clase, la etiqueta, su id y la definición de contexto
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:user_role"  \
  --context-definition-label="user_role"  \
  --context-definition-required
```
