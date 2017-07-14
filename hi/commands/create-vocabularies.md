# create:vocabularies
अपने Drupal 8 एप्लीकेशन के लिए डमी वोकैब्युलरीस बनाएँ।

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | आप कितने वोकैब्युलरीस बनाना चाहते है
--name-words | वोकैब्युलरी के नाम में शब्दों की अधिकतम संख्या

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
