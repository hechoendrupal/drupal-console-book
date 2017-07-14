# create:comments
आपल्या Drupal 8 अनुप्रयोगासाठी डमी टिप तयार करा.

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | आपण किती टिप्पण्या तयार करू इच्छिता?
--title-words | टिप्पणी शीर्षके मध्ये शब्दांची कमाल संख्या.
--time-range | टिप्पण्या किती काळापर्यंत पोचल्या पाहिजेत.

## Available arguments
Argument | Details
---------|-------------
node-id | नोड आयडी जेथे टिप्पण्या तयार केल्या जातील.

## Examples
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
