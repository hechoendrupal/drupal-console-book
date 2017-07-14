# create:vocabularies
Tesztszótárak létrehozása egy Drupal 8 alkalmazáshoz.

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Hány szótár jöjjön létre?
--name-words | A szótárak nevében használt szavak maximális száma

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
