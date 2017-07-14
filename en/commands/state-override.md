# state:override
Override a State key.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal state:override [arguments]
$ sto
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
key | The State key to override.
value | The State value to set.

## commands.generate.doc.gitbook.messages.examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
