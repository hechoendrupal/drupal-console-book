# site:import:local
Import/Configure एक मौजूदा स्थानीय Drupal परियोजना

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | एनवायरनमेंट का नाम जो इम्पोर्ट होने जा रहा है

## Available arguments
Argument | Details
---------|-------------
name | नाम है जो कि साइट config उत्पन्न करने के लिए इस्तेमाल किया जाएगा
directory | मौजूदा Drupal रूट निर्देशिका

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
