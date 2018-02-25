# entity:delete
Elimina una entidad específica

**Uso:**
```
drupal entity:delete [arguments] [options]
ed
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--all | Eliminar todas las entidades del tipo dado

## Argumentos disponibles
Argumento | Detalles
---------|-------------
entity-definition-id | ID de definición de la entidad
entity-id | ID de la entitdad que será eliminada

## Ejemplos
* Eliminar una entidad de tipo de contenido usando su id de nodo
```
drupal entity:delete node 1
```
