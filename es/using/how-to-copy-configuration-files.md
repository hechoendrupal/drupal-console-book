# ¿Cómo copiar archivos de configuración?
La primera tarea que debería hacer tras instalar Drupal Console es ejecutar el comando `init`. Con ello copiará los archivos de configuración del proyecto al directorio `~/.console`. Puede modificar el comportamiento de Drupal Console sobreescribiendo los valores en estos archivos.
 
 ```
 $ drupal init [--override]
 ```
 
### ¿Qué archivos se copian al ejecutar el comando `init`?
```
 ~/.console/
  ├── aliases.yml
  ├── chain
  │   ├── create-data.yml
  │   ├── form-sample.yml
  │   ├── quick-start-mysql.yml
  │   ├── quick-start.yml
  │   ├── sample.yml
  │   ├── site-drop-restore.yml
  │   ├── site-install.yml
  │   └── update-gitbook.yml
  ├── commands.yml
  ├── config.yml
  ├── console.rc
  ├── drupal.fish
  ├── phpcheck.yml
  ├── router.php
  ├── site.mode.yml
  └── sites
      └── sample.yml
```
