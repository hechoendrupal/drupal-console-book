# generate:plugin:rest:resource
Generar un connector de recursos Rest

**Ús:**
```
drupal generate:plugin:rest:resource [options]
gprr
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--module | Nom del mòdul.
--class | Classe del connector de recursos Rest
--plugin-id | Identificador del connector de recursos Rest
--plugin-label | Etiqueta del connector de recursos Rest
--plugin-url | URL del connector de recursos Rest
--plugin-states | Estats del connector de recursos Rest

## Exemples
* Generate a rest resource plugin using GET specifying the module name, the class, the plugin id, its label, the target url and the request type
```
drupal generate:plugin:rest:resource  \
  --module="modulename"  \
  --class="DefaultRestResource"  \
  --plugin-id="default_rest_resource"  \
  --plugin-label="Default rest resource"  \
  --plugin-url="http://rest.resources.example.com"  \
  --plugin-states='GET'
```
