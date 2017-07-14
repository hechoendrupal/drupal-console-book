# debug:user
Muestra los usuarios actuales del sitio

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | Filtra la lista resultante por uids [entre comillas separados por espacios]
--username | Filtra la lista resultante por nombres de usuario [entre comillas separados por espacios]
--mail | Filtra la lista resultante por e-mail de usuarios [entre comillas separados por espacios]
--roles | Indique los roles con los que filtrar el listado de usuarios
--limit | Cuántos usuarios le gustaría listar

## Examples
* Users list on the site
```
drupal debug:user
```
