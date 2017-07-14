# create:comments
अपने Drupal 8 एप्लीकेशन के लिए डमी कमेंट्स बनाएँ।

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | आप कितने भी कमेंट्स बना सकते है
--title-words | कमेंट टाइटल्स में शब्दों की अधिकतम संख्या
--time-range | कमेंट्स दिनांकित किया जाना चाहिए की कितनी दूर समय में वापस होगा

## Available arguments
Argument | Details
---------|-------------
node-id | नोड आईडी जहां कमेंट्स बनाया जाएगा

## Examples
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
