# site:install
Instalar um projeto Drupal

**Utilização:**
```
drupal site:install [arguments] [options]
si
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--langcode | Idioma
--db-type | Tipo de banco de dados
--db-file | Arquivo de configurações do banco de dados
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--site-name | Nome do site
--site-mail | Endereço de email do site
--account-name | Nome de usuário do administrador
--account-mail | Email do administrador
--account-pass | Senha do administrador
--force | Force to reinstall the site

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
profile | Perfil de instalação a ser instalado

## Exemplos
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
