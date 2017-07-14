# generate:command
Generate commands for the console.

**application.gitbook.messages.usage:**
```
drupal generate:command [options]
gco
gcm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | The Class that describes the command. (Must end with the word 'Command').
--name | The Command name.
--container-aware | Is the command aware of the drupal site installation when executed
--services | Load services from the container.
