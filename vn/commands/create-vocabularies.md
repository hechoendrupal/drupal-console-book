# create:vocabularies
Tạo dummy vocabularies cho ứng dụng Drupal 8 của bạn.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Bạn muốn tạo bao nhiêu vocabularies?
--name-words | Maximum number của từ trong vocabulary names

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
