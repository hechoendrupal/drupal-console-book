# ¿Cómo descargar, instalar y servir Drupal 8?

La forma más fácil de probar Drupal 8 en su entorno local es ejecutando el comando `chain` pasando la opción `--file=~/.console/chain/quick-start.yml` como se muestra en el siguiente ejemplo.

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> NOTA: Debe ejecutar `drupal init` antes para copiar en su sistema el archivo `~/.console/chain/quick-start.yml`.

El comando `chain` le ayuda a automatizar la ejecución de comandos, permitiéndole definir un archivo YAML externo que contenga el nombre de definición, opciones y argumentos de varios comandos. Luego se ejecutará esa lista basándose en la secuencia definida en el archivo.
El contenido del archivo `~/.console/chain/quick-start.yml` facilitado es:
```
commands:
  - command: site:new
    arguments:
      site-name: drupal8.dev
      version: 8.0.0
  - command: site:install
    options:
        root: /Users/jmolivas/develop/drupal/sites/drupal8.dev
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

La configuración anterior ejecutará varios comandos: un comando que descargará e instalará Drupal usando SQLite y finalmente arrancará el servidor PHP incorporado. Lo único que le queda ahora por hacer es abrir su navegador y apuntarlo a 127.0.0.1:8088.

Puede duplicar o hacer cambios en el archivo YAML facilitado para:
* añadir comandos para módulos descargados `module:download`
* instalar módulos `module:install` 
* importar configuraciones `config:import` 
* restaurar su base de datos `database:restore` 
* o implementar cualquier otro comando soportado por Drupal Console o un comando personalizado provisto por uno de sus propios módulos.
