# create:vocabularies
Tesztszótárak létrehozása egy Drupal 8 alkalmazáshoz.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:vocabularies [options]
$ crv  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Hány szótár jöjjön létre?
--name-words | A szótárak nevében használt szavak maximális száma

## commands.generate.doc.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
$ drupal create:vocabularies \
  --limit="5" \
  --name-words="5"

```
