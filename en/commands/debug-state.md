# debug:state
Show the current State keys.

**application.gitbook.messages.usage:**
```
drupal debug:state [arguments]
dst
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
key | The State key to debug.

## application.gitbook.messages.examples
* List of the states on the site
```
drupal debug:state
```
* Displays a detail of the state install_task tok from the list of states
```
drupal debug:state install_task
```
