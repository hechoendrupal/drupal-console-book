# create:nodes
Tạo dummy nodes cho ứng dụng Drupal 8 của bạn.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Bạn muốn tạo bao nhiêu node?
--title-words | Maximum number of words in node titles
--time-range | How far back in time should the nodes be dated
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | Content type(s) được sử dụng trong node creation

## Examples
* Provide the content type name.
```
drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
