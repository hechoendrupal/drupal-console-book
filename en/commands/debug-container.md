# debug:container
Displays current services for an application.

**application.gitbook.messages.usage:**
```
drupal debug:container [arguments] [options]
dco
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--parameters | Service name.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## application.gitbook.messages.examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
