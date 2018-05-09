# site:install
Instal·lar un projecte Drupal

**Ús:**
```
drupal site:install [arguments] [options]
si
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--langcode | Idioma del Drupal
--db-type | Tipus de base de dades que de l'instal·lació de Drupal
--db-file | Tipus de fitxer de l'instal·lació de Drupal
--db-host | Nom de l'amfitrió
--db-name | Nom de la base de dades
--db-user | Usuari de la base de dades
--db-pass | Contrasenya de la base de dades
--db-prefix | Prefix de la base de dades
--db-port | Por de la base de dades
--site-name | Nom del lloc Drupal
--site-mail | Compte de correu del lloc Drupal
--account-name | Nom de l'usuari administrador de Drupal
--account-mail | Compte de correu de l'usuari administrador de Drupal
--account-pass | Contrasenya de l'usuari administrador de Drupal
--force | Force to reinstall the site

## Arguments disponibles
Argument | Detalls
---------|-------------
profile | Perfil Drupal a instal·lar

## Exemples
* Install a drupal project specifying installation type, language code, database configuration, site name, site email and admin credential settings
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
