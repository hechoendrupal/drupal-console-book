# node:access:rebuild
Permissões de acesso ao node reconstruídas. A reconstrução irá remover todos os privilégios do conteúdo e substituí-los com permissões baseadas nos módulos e configurações atuais.

**application.gitbook.messages.usage:**
```
drupal node:access:rebuild [options]
nar
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--batch | Processo em modo de lotes.

## application.gitbook.messages.examples
* Reconstruir permissões de acesso a nodes
```
drupal node:access:rebuild --batch
```
