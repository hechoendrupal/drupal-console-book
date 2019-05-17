# Usando un alias de sitio

Drupal Console le permite ejecutar comandos desde su servidor local, pero ejecutarlos realmente tanto en una instalación de Drupal local, como remoto o virtual (VM, Docker) usando los alias de sitio.

Los archivos de alias de sitio usan el formato YAML para facilitar una colección de opciones predefinidas. Una vez que se define un alias, usted puede llamarlo usando un nombre corto.

Un alias de sitio puede estar definido para un sitio remoto usando `type: ssh`. En este caso el comando ssh será usado para ejecutar el comando en la instalación remota.

Los archivos de alias de sitio son descubribles desde las siguientes rutas:

* **Globalmente**: `~/.console/sites/`
* **Por sitio**: `/path/to/site/console/sites/`

## Opciones válidas de un alias de sitio

Listado de opciones clave/valor válidas en el archivo de configuración de un alias de sitio.

* **root**: Directorio raíz del proyecto Drupal.
* **host**: Nombre del dominio del sistema remoto. No requerido en sitios locales.
* **port**: EL puerto que se usará para conectar via SSH. Por defecto, el 22.
* **user**: Nombre de usuario para la conexión por SSH.
* **options**: Matriz (array) de opciones válidas de DrupalConsole.
* **arguments**: Matriz (array) de argumentos válidos de DrupalConsole.
* **extra-options**: Usado sólo cuando el objetivo requiere opciones extra, como la opción tty, autenticación alternativa y/o un archivo de identidad alternativa.
* **type**: Tipo del sitio con el que interactuar. Las opciones permitidas son: `local`, `ssh`, `container`. Por defecto, se usa la opción `local`.

**NOTA:**: Los valores `root` y `type` son obligatorios.
