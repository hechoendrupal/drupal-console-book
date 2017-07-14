# create:vocabularies
आपल्या Drupal 8 अनुप्रयोगासाठी डमी शब्दसंग्रह तयार करा.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | आपण किती शब्दसंग्रह तयार करु इच्छिता?
--name-words | शब्दावलीतील शब्दांची कमाल संख्या.

## Examples
* शब्दसंग्रह नावांमध्ये शब्दांची संख्या तयार करण्यासाठी आणि शब्दांची कमाल संख्या प्रदान करण्यासाठी शब्दसंग्रहांची संख्या द्या.
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
