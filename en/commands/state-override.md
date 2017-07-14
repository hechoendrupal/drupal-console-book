# state:override
Override a State key.

**application.gitbook.messages.usage:**
```
drupal state:override [arguments]
sto
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
key | The State key to override.
value | The State value to set.

## application.gitbook.messages.examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
