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
--langcode | commands.site.install.options.langcode
--db-type | commands.site.install.options.db-type
--db-file | commands.site.install.options.db-file
--db-host | Host de la base de datos
--db-name | Nombre de la base de datos
--db-user | Usuario de la base de datos
--db-pass | Contraseña de la base de datos
--db-prefix | Prefijo de la base de datos
--db-port | Puerto de la base de datos
--site-name | commands.site.install.options.site-name
--site-mail | commands.site.install.options.site-mail
--account-name | commands.site.install.options.account-name
--account-mail | commands.site.install.options.account-mail
--account-pass | commands.site.install.options.account-pass
--force | commands.site.install.options.force

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
