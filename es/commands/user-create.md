# user:create
Crea usuarios para la aplicación

**Usage:**
```
drupal user:create [arguments] [options]
uc
```

## Available options
Option | Details
-------|-------------
--roles | Roles del usuario
--email | E-mail del ususario
--status | Status del usuario

## Available arguments
Argument | Details
---------|-------------
username | Nombre del usuario que será creado
password | Contraseña del usuario

## Examples
* Create user specifying username, password, role, email and status
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* Create admin user specifying username, password, role, email and status
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
