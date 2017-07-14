# create:nodes
अपने Drupal 8 एप्लीकेशन के लिए डमी नोड्स बनाएँ।

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | आप कितने भी नोड्स बना सकते है
--title-words | नोड टाइटल्स में शब्दों की अधिकतम संख्या
--time-range | नोड्स दिनांकित किया जाना चाहिए की कितनी दूर समय में वापस होगा
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | कंटेंट टाइप(स) का उपयोग नोड क्रिएशन में किया जाता है।

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
