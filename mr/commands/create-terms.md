# create:terms
आपल्या Drupal 8 अनुप्रयोगासाठी डमी अटी तयार करा.

**application.gitbook.messages.usage:**
```
drupal create:terms [arguments] [options]
crt
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | आपण किती संज्ञा तयार करू इच्छिता?
--name-words | शब्द नावांमध्ये कमाल संख्या शब्द.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
vocabularies | शब्दसंग्रह तयार करण्यासाठी शब्दसंग्रह(णे).

## application.gitbook.messages.examples
* शब्दसंग्रह संज्ञा नाव प्रदान करा.
```
drupal create:terms vocabulary
```
* शीर्षक शब्द जोडण्याची आणि मर्यादा करण्यासाठी अटींची मर्यादा प्रदान करा.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
