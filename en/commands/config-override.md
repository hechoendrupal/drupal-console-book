# config:override
Override config value in active configuration.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | Configuration name
key | Key
value | Value

## commands.generate.doc.gitbook.messages.examples
* Set the Contact module flood limit to 10.
```
drupal config:override contact.settings flood.limit 10
```
