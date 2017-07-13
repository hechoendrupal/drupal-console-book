# create:terms
Tesztkifejezések létrehozása egy Drupal 8 alkalmazáshoz.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:terms [arguments] [options]
$ crt  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Hány szó jöjjön létre
--name-words | A kifejezések által tartalmazott szavak maximális száma

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
vocabularies | A kifejezések létrehozásakor használandó szótárak

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
