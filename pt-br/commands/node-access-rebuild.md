# node:access:rebuild
Permissões de acesso ao node reconstruídas. A reconstrução irá remover todos os privilégios do conteúdo e substituí-los com permissões baseadas nos módulos e configurações atuais.

**Usage:**
```
drupal node:access:rebuild [options]
nar
```

## Available options
Option | Details
-------|-------------
--batch | Processo em modo de lotes.

## Examples
* Reconstruir permissões de acesso a nodes
```
drupal node:access:rebuild --batch
```
