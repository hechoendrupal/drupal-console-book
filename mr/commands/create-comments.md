# create:comments
आपल्या Drupal 8 अनुप्रयोगासाठी डमी टिप तयार करा.

**application.gitbook.messages.usage:**
```
drupal create:comments [arguments] [options]
crc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | आपण किती टिप्पण्या तयार करू इच्छिता?
--title-words | टिप्पणी शीर्षके मध्ये शब्दांची कमाल संख्या.
--time-range | टिप्पण्या किती काळापर्यंत पोचल्या पाहिजेत.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
node-id | नोड आयडी जेथे टिप्पण्या तयार केल्या जातील.

## application.gitbook.messages.examples
* नोड आयडी द्या जेथे टिप्पण्या निर्माण होतील.
```
drupal create:comments  node-id
```
* कमाल शीर्षक शब्द आणि वेळ श्रेणी निर्माण करण्यासाठी टिप्पण्यांची संख्या प्रदान करा.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
