# generate:plugin:views:field
Generate a custom plugin view field.

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:plugin:views:field [options]
gpvf
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Views plugin field class name
--title | Views plugin field title
--description | Views plugin field description

## commands.generate.doc.gitbook.messages.examples
* Generate a custom view field plugin specifying the module name, the class, a title and its description
```
drupal generate:plugin:views:field  \
  --module="modulename"  \
  --class="CustomViewsField"  \
  --title="Custom views field"  \
  --description="My awesome custom views field plugin."
```
