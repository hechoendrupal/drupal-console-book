# Como baixar, instalar e servir o Drupal 8

A maneira mais fácil de experimentar o Drupal 8 em sua máquina local é executando o comando `chain` e passa a opção` --file = ~ / .console / chain / quick-start.yml 'como mostrado no exemplo a seguir.

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> OBSERVAÇÃO: Você deve executar `drupal init` antes de copiar o` ~ / .console / chain / quick-start.yml` no seu sistema.

O comando `chain` ajuda você a automatizar a execução do comando, permitindo que você defina um arquivo YAML externo que contenha o nome da definição, a opção e os argumentos de vários comandos e execute essa lista com base na seqüência definida no arquivo.

Os conteúdos do arquivo fornecido `~ / .console / chain / quick-start.yml` são:
```
commands:
  - command: site:new
    arguments:
      site-name: drupal8.dev
      version: 8.0.0
  - command: site:install
    options:
        root: /Users/jmolivas/develop/drupal/sites/drupal8.dev
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

A configuração anterior executará vários comandos, neste caso, comandos que irão baixar e instalar o Drupal usando o SQLite e, finalmente, iniciar o servidor incorporado do PHP, agora você só precisa abrir seu navegador e apontá-lo para 127.0.0.1:8088.

Você pode duplicar ou fazer alterações no arquivo YAML fornecido, para adicionar comandos para módulos de download `module: download`, instalar módulos` module: install`, importar configurações `config: import` e restaurar o banco de dados` database: restore` ou any Outro comando fornecido pelo DrupalConsole ou um comando personalizado pelo seu próprio módulo.