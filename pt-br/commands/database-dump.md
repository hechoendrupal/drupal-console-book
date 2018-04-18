# database:dump
Dump da estrutura e conteúdos da base de dados e tabelas MySQL

**Utilização:**
```
drupal database:dump [arguments] [options]
dbdu
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--file |  O nome do arquivo de backup do banco de dados
--gz | Pass this option if you want the sql result file gzipped

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
database | Senha da base de dados em settings.php

## Exemplos
* Dump default database or the one specified on the argument
```
drupal database:dump \
  <database>
```
* Dump in gz compressed format
```
drupal database:dump \
  --gz
```
