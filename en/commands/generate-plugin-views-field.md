# generate:plugin:views:field
Generate a custom plugin view field.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Views plugin field class name
--title | Views plugin field title
--description | Views plugin field description

## application.gitbook.messages.examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
