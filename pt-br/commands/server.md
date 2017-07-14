# server
Executar o servidor PHP atual

**application.gitbook.messages.usage:**
```
drupal server [arguments]
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
address | Valores de endereço:porta

## application.gitbook.messages.examples
* Executar com o endereço padrão 127.0.0.1:8088
```
drupal server
```
* Executar passando um endereço e porta diferentes
```
drupal server 127.0.0.1:8089
```
* Executar com os argumentos padrões, porém usando a opção --root para definir o diretório raíz do site
```
drupal --root=/var/www/drupal8.dev server
```
