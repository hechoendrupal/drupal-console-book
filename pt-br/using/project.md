# Usando o projeto

O Drupal Console fornece dois tipos de comandos, comandos 'stand-alone' e `container aware`.

**Comandos stand alone:**
Esses comandos podem ser executados fora de uma raiz do site Drupal 8.
 
**Comandos container aware:**
Esses comandos devem ser executados dentro de uma raiz do site Drupal 8.

### Executando o Drupal Console fora de uma raiz do site Drupal 
Você pode executar o Drupal Console de qualquer diretório em seu sistema, usando a opção `--root` para definir a raiz Drupal a ser usada na execução do comando
```
$ drupal --root=/var/www/drupal8.dev cr all
```

**OBSERVAÇÃO:** Possíveis mensagens ao executar Drupal Console fora de uma raiz do site Drupal e nenhuma opção `--root` fornecida.

Ao executar o projeto fora de uma raiz do site Drupal 8, será exibida a seguinte mensagem.  
> In order to list all of the available commands, you should run this inside a drupal root directory.

Ao executar o projeto dentro de uma raiz do site do Drupal 8, mas o site ainda não está instalado, a seguinte mensagem será exibida.
> In order to list all of the available commands you should install drupal first.