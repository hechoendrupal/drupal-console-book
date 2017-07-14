# site:install
एक Drupal प्रकल्प स्थापित.

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
--db-host | डेटाबेस यजमान.
--db-name | डेटाबेस नाव.
--db-user | डेटाबेस वापरकर्ता.
--db-pass | डेटाबेस पास.
--db-prefix | डेटाबेस उपसर्ग.
--db-port | डेटाबेस हस्तांतरण.
--site-name | commands.site.install.options.site-name
--site-mail | commands.site.install.options.site-mail
--account-name | commands.site.install.options.account-name
--account-mail | commands.site.install.options.account-mail
--account-pass | commands.site.install.options.account-pass
--force | commands.site.install.options.force

## Available arguments
Argument | Details
---------|-------------
profile | Drupal प्रोफाइल स्थापित करणे.

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
