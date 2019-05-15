# debug:router
Muestra las rutas actuales de la aplicación o la información detallada de una ruta en particular

**Uso:**
```
drupal debug:router [arguments]
dr
rod
```

## Argumentos disponibles
Argumento | Detalles
---------|-------------
route-name | Nombres de ruta

## Ejemplos
* Muestra todas las rutas disponibles en la aplicación
```
drupal rod
```
* Muestra la información detallada de la ruta user.page (/user)
```
drupal rod user.page
```
* Muestra la lista de rutas en el sitio
```
drupal debug:router
```
* Muestra información sobre la ruta de user.login
```
drupal debug:router user.login
```
* Muestra inforamción para las rutas con el patrón (/user/login)
```
drupal debug:router --pattern=/user/login
```
