# create:terms
Tạo dummy terms cho ứng dụng Drupal 8 của bạn.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:terms [arguments] [options]
$ crt  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Bao nhiêu terms bạn muốn tạo?
--name-words | Maximum number of words in term names

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
vocabularies | Vocabularie(s) được sử dụng trong terms creation

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
