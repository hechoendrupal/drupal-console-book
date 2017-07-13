# node:access:rebuild
Permissões de acesso ao node reconstruídas. A reconstrução irá remover todos os privilégios do conteúdo e substituí-los com permissões baseadas nos módulos e configurações atuais.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal node:access:rebuild [options]
$ nar  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--batch | Processo em modo de lotes.

## commands.generate.doc.gitbook.messages.examples
* Reconstruir permissões de acesso a nodes
```
$ drupal node:access:rebuild --batch
```
