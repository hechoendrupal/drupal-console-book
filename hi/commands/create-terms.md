# create:terms
अपने Drupal 8 एप्लीकेशन के लिए डमी टर्म्ज़ बनाएँ।

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:terms [arguments] [options]
$ crt  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | आप कितने टर्म्ज़ बनाना चाहते हैं
--name-words | टर्म नेम्स में शब्दों की अधिकतम संख्या

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
vocabularies | टर्म्ज़ के निर्माण में प्रयोग की जाने वाली वोकेबुलरी(स)

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
