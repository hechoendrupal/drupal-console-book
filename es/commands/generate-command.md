# generate:command
Genera un comando para la consola.

**Uso:**
```
drupal generate:command [options]
gco
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--extension | Nombre de la extensión.
--extension-type | Tipo de la extensión.
--class | Nombre de la Clase de Comandos
--name | Nombre del comando.
--initialize | Añadir método initialize.
--interact | Añadir método interactivo.
--container-aware | Conoce el comando acerca de la instalación del sitio drupal cuando sea ejecutado
--services | Cargar servicios desde el contenedor.
--generator | Añadir una clase class Generator para este comando.

## Ejemplos
* Generar un comando especificando el nombre de extensión, el tipo, la clase y el nombre.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
