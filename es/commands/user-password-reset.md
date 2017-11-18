# user:password:reset
Restablece la contraseña de un usuario específico.

**Uso:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
user | Nombre de usuario o ID
password | Contraseña en formato de texto

## Ejemplos
* Actualizar la constraseña especificando el ID de usuario y la nueva contraseña
```
drupal user:password:reset  2 p455w0rd
```
* Actualizar la contraseña especificando el usuario jmolivas y la nueva contraseña
```
drupal user:password:reset jmolivas p455w0rd
```
