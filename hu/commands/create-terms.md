# create:terms
Tesztkifejezések létrehozása egy Drupal 8 alkalmazáshoz.

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Hány szó jöjjön létre
--name-words | A kifejezések által tartalmazott szavak maximális száma

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | A kifejezések létrehozásakor használandó szótárak

## application.gitbook.messages.examples
* Provide the vocabulary term name.
```
drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
