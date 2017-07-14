# generate:entity:content
Generate a new content entity

**commands.generate.doc.gitbook.messages.usage:**
```
drupal generate:entity:content [options]
geco
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | The Module name.
--entity-class | The content entity class
--entity-name | The content entity name
--base-path | The base-path for the content entity routes
--label | The label
--has-bundles | Entity has bundles
--is-translatable | Content entity translatable
--revisionable | commands.generate.entity.content.options.revisionable

## commands.generate.doc.gitbook.messages.examples
* Generate a content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* Generate a translatable and revisionable content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
