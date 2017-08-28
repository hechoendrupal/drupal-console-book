# Requisitos do projeto

## Baixar Git
Recomendamos o download do Git de [http://git-scm.com/downloads](http://git-scm.com/downloads)

## Baixar Composer

Execute isso no seu terminal para obter a versão mais recente do Composer:
```
curl -sS https://getcomposer.org/installer | php
```
Ou se você não tem curl:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
Este script instalador simplesmente verificará algumas configurações do php.ini, avisará se eles estiverem configurados incorretamente e, em seguida, baixe o mais recente compsoe.phar no diretório atual

Você pode executar este comando de terminal para tornar o Composer facilmente acessível, de qualquer lugar em seu sistema:

```
$ mv composer.phar /usr/local/bin/composer
```

## Baixar Drupal 8
O projeto Drupal Console só suporta o Drupal 8; Que você precisará baixar e instalar localmente.
### Baixar Drupal
```
$ drupal site:new drupal8.dev 8.0.0
$ cd drupal8.dev
```
### Instalar Drupal usando MySQL:
```
$ drupal site:install standard --langcode=en --db-type=mysql --db-host=127.0.0.1 
  --db-name=drupal --db-user=root --db-pass=root --db-port=3306 
  --site-name="Drupal 8 Site Install" --site-mail=admin@example.com 
  --account-name=admin --account-mail=admin@example.com --account-pass=admin -n
```
### Instalar Drupal usando SQLite:
```
$ drupal site:install standard --langcode=en --db-type=sqlite 
  --db-file=sites/default/files/.ht.sqlite --site-name="Drupal 8 Site Install" 
  --site-mail=admin@example.com --account-name=admin --account-mail=admin@example.com
  --account-pass=admin -n
```
### Iniciar o servidor built-in do PHP
```
$ drupal server
```
Certifique-se de usar suas próprias credenciais de usuário e banco de dados ao executar `site: install` e nunca root do usuário na produção. Neste código de exemplo, aceitamos todas as perguntas interativas, ou seja, respondendo *"sim"* ao passar o argumento `-y`
