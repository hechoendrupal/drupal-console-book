# create:vocabularies
Tạo dummy vocabularies cho ứng dụng Drupal 8 của bạn.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:vocabularies [options]
$ crv  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Bạn muốn tạo bao nhiêu vocabularies?
--name-words | Maximum number của từ trong vocabulary names

## commands.generate.doc.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
$ drupal create:vocabularies \
  --limit="5" \
  --name-words="5"

```
