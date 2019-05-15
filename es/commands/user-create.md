# user:create
Crea usuarios en el sitio

**Uso:**
```
drupal user:create [arguments] [options]
uc
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--roles | Roles del usuario
--email | Correo electrónico del usuario
--status | Estado del usuario

## Argumentos disponibles
Argumento | Detalles
---------|-------------
username | Nombre del usuario que será creado
password | Contraseña del usuario

## Ejemplos
* Crear usuario especificando nombre de usuario, contraseña, rol, correo electrónico y estado
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* Crear usuario administrador especificando nombre de usuario, contraseña, rol, correo electrónico y estado
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
