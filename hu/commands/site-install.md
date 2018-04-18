# site:install
Drupal projekt telepítése

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | A Drupal nyelve
--db-type | A telepítéskor használandó Drupal adatbázis
--db-file | A telepítéskor használandó Drupal adatbázisfájl
--db-host | Adatbázis-gazdagép
--db-name | Adatbázis neve
--db-user | Adatbázis-felhasználó
--db-pass | Adatbázis jelszó
--db-prefix | Adatbázis előtag
--db-port | Adatbázis port
--site-name | A Drupal webhely neve
--site-mail | A Drupal webhely e-mail címe
--account-name | A Drupal adminisztrátori fiók neve
--account-mail | A Drupal adminisztrátori fiók e-mail címe
--account-pass | A Drupal adminisztrátori fiók jelszava
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Telepítendő Drupal profil

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
