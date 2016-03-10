# Usando el proyecto

Drupal Console ofrece dos tipos de comandos, son `stand alone` y `container aware`.

**Comandos stand alone:**
Estos comandos pueden ser ejecutados fuera del diretorio raíz de su sitio Drupal 8.
 
**Comandos container aware:**
Estos comandos deben ser ejecutados dentro del directorio raíz del sitio Drupal 8.

### Ejecutando Drupal Console fuera del raíz del sitio Drupal 8 
Puede ejecutar Drupal Console desde cualquier directorio en su sistema local usando la opción  `--root` para definir el directorio raíz del sitio Drupal al que se referirá la ejecución del comando. 
```
$ drupal --root=/var/www/drupal8.dev cr all
```

**NOTA:** Si ejecuta Drupal Console fuera del raíz de un sitio Drupal y sin la opción `--root` pueden aparecer mensajes de advertencia.

Cuando ejecute el proyecto fuera del raíz de su sitio Drupal 8, aparecerá el siguiente mensaje.  
> Para listar todos los comandos disponibles Ud. debería ejecutar este comando dentro de un directorio raíz de un sitio Drupal.

Cuando ejecute el proyecto dentro del raíz de su sitio Drupal 8, pero el sitio aún no ha sido instalado, aparecerá el siguiente mensaje.
> Para listar todos los comandos disponibles Ud. debería instalar Drupal antes.
