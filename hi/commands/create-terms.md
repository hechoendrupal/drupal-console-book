# create:terms
अपने Drupal 8 एप्लीकेशन के लिए डमी टर्म्ज़ बनाएँ।

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | आप कितने टर्म्ज़ बनाना चाहते हैं
--name-words | टर्म नेम्स में शब्दों की अधिकतम संख्या

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | टर्म्ज़ के निर्माण में प्रयोग की जाने वाली वोकेबुलरी(स)

## application.gitbook.messages.examples
* Provide the vocabulary term name.
```
drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
