# config:override
Suprascrie valoarea de configurare în configurarea activă.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:override [arguments]
$ co  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | Configuration name
key | Cheie
value | Valoare

## commands.generate.doc.gitbook.messages.examples
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
