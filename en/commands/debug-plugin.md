# debug:plugin
Displays all plugin types.

**application.gitbook.messages.usage:**
```
drupal debug:plugin [arguments]
dpl
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
type | Plugin type
id | Plugin ID

## application.gitbook.messages.examples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
