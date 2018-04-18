# site:install
एक Drupal परियोजना स्थापित करें

**Usage:**
```
drupal site:install [arguments] [options]
si
```

## Available options
Option | Details
-------|-------------
--langcode | Drupal भाषा
--db-type | Drupal के डेटाबेस प्रकार स्थापित करने में उपयोग किया जाना है
--db-file | Drupal के डाटाबेस फ़ाइल को स्थापित करने में उपयोग किया जाना है
--db-host | मेजबान डेटाबेस
--db-name | डेटाबेस का नाम
--db-user | डेटाबेस उपयोगकर्ता
--db-pass | डेटाबेस पासवर्ड
--db-prefix | डेटाबेस उपसर्ग
--db-port | डेटाबेस पोर्ट
--site-name | Drupal साइट का नाम
--site-mail | Drupal साइट का नाम
--account-name | Drupal के व्यवस्थापक खाते का नाम
--account-mail | Drupal व्यवस्थापक का मेल खाता 
--account-pass | व्यवस्थापक खाते का पासवर्ड
--force | Force to reinstall the site

## Available arguments
Argument | Details
---------|-------------
profile | Drupal प्रोफ़ाइल स्थापित किया जाना है

## Examples
* Install a drupal project specifying installation type, language code, database configuration, site name, site email and admin credential settings
```
drupal site:install  standard  \
  --langcode="en"  \
  --db-type="mysql"  \
  --db-host="127.0.0.1"  \
  --db-name="drupal8"  \
  --db-user="u53rn4m3"  \
  --db-pass="dbp455"  \
  --db-port="3306"  \
  --site-name="Drupal 8"  \
  --site-mail="admin@example.com"  \
  --account-name="admin"  \
  --account-mail="admin@example.com"  \
  --account-pass="p455w0rd"
```
