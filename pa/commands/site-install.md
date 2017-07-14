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
--langcode | commands.site.install.options.langcode
--db-type | commands.site.install.options.db-type
--db-file | commands.site.install.options.db-file
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--site-name | commands.site.install.options.site-name
--site-mail | commands.site.install.options.site-mail
--account-name | commands.site.install.options.account-name
--account-mail | commands.site.install.options.account-mail
--account-pass | commands.site.install.options.account-pass
--force | commands.site.install.options.force

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
