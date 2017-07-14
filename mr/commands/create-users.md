# create:users
आपल्या Drupal 8 अनुप्रयोगासाठी डमी वापरकर्ते तयार करा.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | आपण किती वापरकर्ते तयार करु इच्छिता?
--password | तयार केलेल्या वापरकर्त्यांसाठी संकेतशब्द.
--time-range | वापरकर्त्यांनी कित्येक वेळापूर्वी वेळेची नोंद केली पाहिजे.

## Available arguments
Argument | Details
---------|-------------
roles | वापरकर्त्याच्या निर्मितीमध्ये वापरल्या जाणार्या भूमिका.

## Examples
* वापरकर्ता भूमिका प्रदान करा.
```
drupal create:users role
```
* तयार करण्यासाठी वापरकर्त्यांची संख्या, संकेतशब्द आणि वेळ श्रेणी प्रदान करा.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
