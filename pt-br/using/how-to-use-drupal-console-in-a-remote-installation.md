# Como usar o Drupal Console em uma instalação remota do site

O Console Drupal permite que você execute comandos em seu servidor local, mas execute-os em um servidor remoto.

Você pode aproveitar esse recurso, usando a opção `--target` e passando o nome do site remoto com o qual deseja interagir.  
```
$ drupal --target=sample.dev cr all
```

Configurar o seu computador local para usar um site remoto requer uma pequena configuração.

### Editar configuração global 
Você pode fornecer configuração global para conexões remotas no arquivo `~ / .console / config.yml`. Esta informação é agrupada na chave 'remote'

```
application:
  ...
  remote:
    user: root
    port: 22
    console: /usr/local/bin/drupal
    options:
    arguments:
    keys:
      public: ~/.ssh/id_rsa.pub
      private: ~/.ssh/id_rsa
      passphrase: ~/.ssh/passphrase.txt
```

### Editar configuração específica de site
Você pode fornecer a configuração específica do site, duplicando o arquivo do site copiado em `~ / .console/sites/sample.yml` com um novo mesmo em` ~ /.console/sites/ `.

```
local:
  root: /var/www/drupal8.dev
  host: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  console: /var/www/html/docroot/console.phar
```

### Debugar sites.
Você pode listar todos os sites locais e remotos conhecidos executando o comando `site: debug`.
```
$ drupal site:debug

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

Você pode mostrar os detalhes da configuração do site passando o nome do site como argumento para o comando `site: debug`. 
```
$ drupal site:debug sample.dev

user: drupal
port: 22
console: /usr/local/bin/drupal
options:
arguments: 
keys:
    public: ~/.ssh/id_rsa.pub
    private: ~/.ssh/id_rsa
    passphrase: ~/.ssh/passphrase.txt
root: /var/www/html/drupal
host: 140.211.10.62
remote: true
```

**OBSERVAÇÃO:** Como você pode notar a configuração global e a configuração específica do site são mescladas ao depurar um site. Você pode substituir qualquer configuração global adicionando essas chaves na configuração específica do site.  
