# site:install
Install a Drupal project

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Drupal language
--db-type | Drupal Database type to be used in install
--db-file | Drupal Database file to be used in install
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--site-name | Drupal site name
--site-mail | Drupal site mail
--account-name | Drupal administrator account name
--account-mail | Drupal administrator account mail
--account-pass | Drupal administrator account password
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Drupal Profile to be installed

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
