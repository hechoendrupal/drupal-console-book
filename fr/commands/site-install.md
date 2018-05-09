# site:install
Installe un site Drupal

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Langue Drupal
--db-type | Type de base de données à utiliser lors de l'installation
--db-file | Fichier de base de données Drupal à utiliser lors de l'installation
--db-host | Serveur de la base de données
--db-name | Nom de la base de données
--db-user | Utilisateur de la base de données
--db-pass | Mot de passe de la base de données
--db-prefix | Préfixe de la base de données
--db-port | Port de la base de données
--site-name | Nom du site Drupal
--site-mail | Courriel du site Drupal
--account-name | Nom du compte administrateur Drupal
--account-mail | Courriel du compte administrateur Drupal
--account-pass | Mot de passe du compte administrateur Drupal
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Profil Drupal à installer

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
