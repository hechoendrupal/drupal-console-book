# Instalando o Drupal Console no Windows
No Windows existem duas maneiras de instalar o console drupal. Uma usa Git Bash, a outra usa um prompt de comando do Windows. Recomendo usar o utilitário Git Bash a partir do pacote de programas Git para Windows (anteriormente msysgit), uma vez que é a única maneira de usar o console drupal sem prefixá-lo com o php.

## Usando Git Bash:
Se você usa o Drupal Console no Git Bash, instale os pacotes abaixo:

* [Git for Windows](https://git-for-windows.github.io/)
* [Composer](https://github.com/composer/windows-setup)
* [PHP For Windows](http://windows.php.net/download/)
* [sqlite-tools-win32-x86](https://www.sqlite.org/download.html)

### Atualizar a variável de ambiente PATH

Após a instalação, você deve incluir php.exe e sqlite3.exe em sua variável de ambiente PATH.
Por exemplo, se você extraiu "PHP for Windows" em "C: \ php" e extraiu "sqlite-tools-win32-x86" em "C: \ sqlite", você pode configurar a variável de ambiente PATH como abaixo do prompt de comando.
```
SETX /M PATH "%PATH%;C:\php;C:\sqlite"
```

### Configurar php.ini

O Drupal Console requer algumas extensões. Habilite essas extensões no seu php.ini.
```
extension=php_gd2.dll
extension=php_pdo_sqlite.dll
extension=php_curl.dll
extension=php_openssl.dll
```

Recomendamos ativar as seguintes extensões para permitir que você use seu próprio idioma.
```
extension=php_intl.dll
extension=php_mbstring.dll
```

#### Definir certificados

Coloque informações de certificados fornecidas pelo Git para Windows
```
curl.cainfo = C:\Program Files\Git\usr\ssl\certs\ca-bundle.crt;
```

### Instalando Drupal Console globalmente usando composer:
```
$ composer global require drupal/console:@stable
```

### Você pode agora executar o console usando:

```
$ drupal
```
ou execute uma das cadeias disponíveis, para executar uma instalação rápida, execute o seguinte comando
```
$ drupal chain --file="C:\Users\username\.console\chain\quick-start.yml"
```

**OBSERVAÇÃO:** Você deve fornecer o caminho "Windows-style" para a opção `file`