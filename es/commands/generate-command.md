# generate:command
Genera un comando para la consola.

**Usage:**
```
drupal generate:command [options]
gco
gcm
```

## Available options
Option | Details
-------|-------------
--extension | Nombre de la extensión.
--extension-type | Tipo de la extensión.
--class | Nombre de la Clase de Comandos
--name | Nombre del comando.
--container-aware | Conoce el comando acerca de la instalación del sitio drupal cuando sea ejecutado
--services | Cargar servicios desde el contenedor.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
