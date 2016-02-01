# Cómo copiar archivos de configuración
La primera tarea que debería hacer tras instalar Drupal Console es ejecutar el comando `init`. Con ello copiará los archivos de configuración del proyecto a su directorio `~/.console`. Puede modificar el comportamiento de Drupal Console sobreescribiendo los valores en estos archivos.
 
 ```
 $ drupal init [--override]
 ```
 
### ¿Qué archivos se copian al ejecutar el comando `init`?
```
 ~/.console/ 
 ├── aliases.yml 
 ├── chain
 │   ├── quick-start.yml
 │   └── sample.yml 
 ├── config.yml 
 ├── console.rc 
 ├── drupal.fish 
 └── sites 
     └── sample.yml 
```
