# create:comments
अपने Drupal 8 एप्लीकेशन के लिए डमी कमेंट्स बनाएँ।

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:comments [arguments] [options]
$ crc  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | आप कितने भी कमेंट्स बना सकते है
--title-words | कमेंट टाइटल्स में शब्दों की अधिकतम संख्या
--time-range | कमेंट्स दिनांकित किया जाना चाहिए की कितनी दूर समय में वापस होगा

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
node-id | नोड आईडी जहां कमेंट्स बनाया जाएगा

## commands.generate.doc.gitbook.messages.examples
* Provide the node id where the comments will be generated.
```
$ drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
$ drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"

```
