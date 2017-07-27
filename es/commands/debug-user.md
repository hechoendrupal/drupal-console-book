# debug:user
Muestra los usuarios existentes en el sitio

**Uso:**
```
drupal debug:user [options]
dus
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--uid | Filtra el listado de resultados por uids [entre comillas, separados por espacios]
--username | Filtra el listado de resultados por nombres de usuario [entre comillas, separados por espacios]
--mail | Filtra el listado de resultados por e-mails [entre comillas, separados por espacios]
--roles | Roles a filtrar la inspección
--limit | Cuántos usuarios le gustaría que se listaran en la inspección

## Ejemplos
* Listar todos los usuarios del sitio
```
drupal debug:user
```
