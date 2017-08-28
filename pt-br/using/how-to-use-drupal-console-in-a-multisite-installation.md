# Como usar o Drupal Console em uma instalação multi-site 
 
O Console Drupal oferece suporte para instalações multi-site Drupal. Este projeto fornece o comando `multisite: debug` para depurar instalações multi-site e a opção` --uri 'para interagir com instalações multi-site
 
### Como listar todos os vários sites conhecidos
```
$ drupal multisite:debug

+---------------------+--------------------------------+
| Site                | Directory                      |
+---------------------+--------------------------------+
| drupal8.dev         | /var/www/drupal8.dev/default   |
| drupal8.multi.dev   | /var/www/drupal8.dev/multi.dev |
+---------------------+--------------------------------+

 Como executar um comando contra uma instalação multi-site: <port>.<domain>.<path>
```

### How to execute a command against a multi-site installation
```
$ drupal --uri=http://drupal8.multi.dev cr all
```
