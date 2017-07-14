# create:nodes
आपल्या Drupal 8 अनुप्रयोगासाठी डमी नोड्स तयार करा.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | नोडमध्ये वापरण्याजोगी सामग्री प्रकार(य्स) आपण तयार केलेल्या किती नोडस् तयार करणे.
--title-words | नोड शीर्षकेतील शब्दांची कमाल संख्या.
--time-range | नोडचे किती काळचे काळ असावे?
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | नोड निर्मितीत वापरण्यासाठी सामग्री प्रकार.

## Examples
* सामग्री प्रकार नाव प्रदान करा.
```
drupal create:nodes content-name
```
* प्रकाशनांची मर्यादा, शीर्षक शब्दांची मर्यादा, वेळ श्रेणी आणि भाषा प्रदान करा.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
