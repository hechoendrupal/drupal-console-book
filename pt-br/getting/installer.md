# Utilizando o instalador do Drupal Console
Você pode instalar o Drupal Console localmente executando o instalador em seu diretório de projeto, o instalador cuidará de baixar os arquivos necessários para executar o console drupal em seu computador.

## Usando curl:
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## Ou se você não tiver curl:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## Agora você pode executar usando:
```
$ php drupal.phar
```
Você pode colocar este arquivo em qualquer lugar que desejar. Se você colocá-lo no seu PATH, você pode acessá-lo globalmente. Em sistemas unix você pode até torná-lo executável e invocá-lo sem php.

### Acesso de qualquer lugar do seu sistema
```
$ mv drupal.phar /usr/local/bin/drupal
```

### Aplicar permissões de execução no arquivo baixado:
```
$ chmod +x /usr/local/bin/drupal
```

#### Agora você pode executar usando:
```
$ drupal
```

**OBSERVAÇÃO:** O nome `drupal` é apenas um alias, você pode nomeá-lo qualquer coisa que você preferir.
