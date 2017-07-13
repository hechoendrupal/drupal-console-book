# cron:execute
Executar cron de um módulo específico ou todos para executar todas as implementações

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal cron:execute [arguments]
$ croe  
$ cre  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | O nome do módulo.

## commands.generate.doc.gitbook.messages.examples
* Execute the cron globally
```
$ drupal cron:execute

```
* Execute the cron on the specified module
```
$ drupal cron:execute \
  <module>

```
