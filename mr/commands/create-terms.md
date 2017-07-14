# create:terms
आपल्या Drupal 8 अनुप्रयोगासाठी डमी अटी तयार करा.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | आपण किती संज्ञा तयार करू इच्छिता?
--name-words | शब्द नावांमध्ये कमाल संख्या शब्द.

## Available arguments
Argument | Details
---------|-------------
vocabularies | शब्दसंग्रह तयार करण्यासाठी शब्दसंग्रह(णे).

## Examples
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
