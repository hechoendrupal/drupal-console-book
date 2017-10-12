# user:role
Añadir/eliminar un rol de un usuario dado

**Uso:**
```
drupal user:role [arguments]
ur
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
operation | Añadir o eliminar
user | El usuario en cuestión (sólo uno)
role | Roles a añadir o eliminar. Por favor, indique el nombre máquina (sólo uno)

## Ejemplos
* Añadir el rol administrador al usuario administrador espacificando el nombre de usuario y el rol
```
drupal user:role  add admin administrator
```
* Eliminar el rol administrador del usuario administrador espacificando el nombre de usuario y el rol
```
drupal user:role  remove admin administrator
```
