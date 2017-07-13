# debug:container
Displays current services for an application.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:container [arguments] [options]
$ dco  
$ cod  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--parameters | Service name.

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## commands.generate.doc.gitbook.messages.examples
* Displays the views.views_data_helper services
```
$ drupal debug:container views.views_data_helper

```
