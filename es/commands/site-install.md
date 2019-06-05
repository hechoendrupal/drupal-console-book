# site:install
Instala un proyecto Drupal

**Uso:**
```
drupal site:install [arguments] [options]
si
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--langcode | Idioma
--db-type | Tipo de base de datos
--db-file | Archivo de base de datos de Drupal a usar en la instalación
--db-host | Host de la base de datos
--db-name | Nombre de la base de datos
--db-user | Usuario de la base de datos
--db-pass | Contraseña de la base de datos
--db-prefix | Prefijo de la base de datos
--db-port | Puerto de la base de datos
--site-name | Nombre del sitio
--site-mail | Dirección de correo electrónico del sitio
--account-name | Nombre de la cuenta de administrador
--account-mail | Correo electrónico de la cuenta de administrador
--account-pass | Contraseña de la cuenta de administrador
--force | Forzar para reinstalar el sitio

## Argumentos disponibles
Argumento | Detalles
---------|-------------
profile | Perfil de Drupal que será instalado

## Ejemplos
* Instalar un proyecto Drupal especificando el tipo de instalación, código de idioma, configuración de la base de datos, nombre del sitio, e-mail del sitio y credenciales del usuario admin
```
drupal site:install  standard  \
  --langcode="en"  \
  --db-type="mysql"  \
  --db-host="127.0.0.1"  \
  --db-name="drupal8"  \
  --db-user="u53rn4m3"  \
  --db-pass="dbp455"  \
  --db-port="3306"  \
  --site-name="Drupal 8"  \
  --site-mail="admin@example.com"  \
  --account-name="admin"  \
  --account-mail="admin@example.com"  \
  --account-pass="p455w0rd"
```
* Instalar un proyecto drupal usando una url de mysql
```
drupal site:install  standard  mysql://dbUser:dbPass@dbHost/dbName \
  --langcode="en"  \
  --site-name="Drupal 8"  \
  --site-mail="admin@example.com"  \
  --account-name="admin"  \
  --account-mail="admin@example.com"  \
  --account-pass="p455w0rd"
```
