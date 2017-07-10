# create:terms
Create dummy terms for your Drupal 8 application.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:terms [arguments] [options]
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | How many terms would you like to create
--name-words | Maximum number of words in term names

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
vocabularies | Vocabulary(s) to be used in terms creation

## commands.generate.doc.gitbook.messages.examples
* Provide the vocabulary term name.
```
$ drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
$ drupal create:terms tags \
  --limit="10" \
  --name-words="5"

```
