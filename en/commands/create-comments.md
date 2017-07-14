# create:comments
Create dummy comments for your Drupal 8 application.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:comments [arguments] [options]
$ crc
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | How many comments would you like to create
--title-words | Maximum number of words in comment titles
--time-range | How far back in time should the comments be dated

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
node-id | Node ID where the comments will be created

## commands.generate.doc.gitbook.messages.examples
* Provide the node id where the comments will be generated.
```
drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
