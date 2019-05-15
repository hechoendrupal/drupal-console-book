# generate:site:alias
Genera un alias del sitio.

**Uso:**
```
drupal generate:site:alias [options]
gsa
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--site | Utilizar el sitio local como destino.
--name | Nombre del sitio.
--environment | Nombre del entorno.
--type | Tipo del sitio.
--composer-root | El directorio raíz del proyecto Drupal.
--site-uri | Uri del Drupal (para multisitios).
--host | La ip/dominio del sitio remoto. No obligatorio para sitios locales.
--user | El nombre de usuario a usar al conectar por ssh.
--port | El puesto a usar al conectar por ssh.
--extra-options | Usado sólo cuando el objetivo requiere opciones extra, como un método de autenticación alternativa y/o un archivo de identidad alternativo.
--directory | Directorio para guardar el alias del sitio generado.
