# generate:entity:config
Generate a new config entity

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:entity:config [options]
gec
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--entity-class | The config entity class
--entity-name | The config entity name
--base-path | The base-path for the config entity routes
--label | The label
--bundle-of | Acts as bundle for content entities

## commands.generate.doc.gitbook.messages.examples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
