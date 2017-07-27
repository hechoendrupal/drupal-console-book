# debug:plugin
Muestra todos los tipos de plugins.

**Uso:**
```
drupal debug:plugin [arguments]
dpl
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
type | Tipo de plugin
id | ID de plugin

## Ejemplos
* Listar todos los plugins del sitio
```
drupal debug:plugin
```
* Muestra información de los plugins de bloques
```
drupal debug:plugin block
```
* Mostrar información de displays rotos de plugins de bloque
```
drupal debug:plugin block broken
```
