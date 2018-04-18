# site:install
Instalează un proiect Drupal

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Limba proiectului
--db-type | Tipul bazei de date care va fi folosit la instalarea proiectului
--db-file | Drupal Database file to be used in install
--db-host | Gazda bazei de date
--db-name | Numele bazei de date
--db-user | Utilizatorul bazei de date
--db-pass | Parola bazei de date
--db-prefix | Prefixul bazei de date
--db-port | Portul bazei de date
--site-name | Numele sitului drupal
--site-mail | Adresa de email a sitului
--account-name | Numele de utilizator al administratorului sitului
--account-mail | Adresa de email a administratorului sitului
--account-pass | Parola administratorului sitului
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Profilul Drupal care va fi instalat

## Examples
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
