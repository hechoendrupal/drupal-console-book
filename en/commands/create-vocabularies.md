# create:vocabularies
Create dummy vocabularies for your Drupal 8 application.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:vocabularies [options]
$ crv
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | How many vocabularies would you like to create
--name-words | Maximum number of words in vocabulary names

## commands.generate.doc.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
