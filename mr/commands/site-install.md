# site:install
एक Drupal प्रकल्प स्थापित.

**वापर:**
```
drupal site:install [arguments] [options]
si
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--langcode | Drupal भाषा
--db-type | इन्स्टॉलमध्ये वापरण्याकरिता Drupal डाटाबेस प्रकार.
--db-file | अधिष्ठापने मध्ये वापरण्याकरिता Drupal डेटाबेस फाइल,
--db-host | डेटाबेस यजमान.
--db-name | डेटाबेस नाव.
--db-user | डेटाबेस वापरकर्ता.
--db-pass | डेटाबेस पास.
--db-prefix | डेटाबेस उपसर्ग.
--db-port | डेटाबेस हस्तांतरण.
--site-name | Drupal साइट नाव
--site-mail | Drupal साइट मेल
--account-name | Drupal प्रशासक खाते नाव.
--account-mail | Drupal प्रशासक खाते मेल.
--account-pass | Drupal प्रशासक खाते संकेतशब्द.
--force | Force to reinstall the site

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
profile | Drupal प्रोफाइल स्थापित करणे.

## उदाहरणे
* स्थापना प्रकार, भाषा कोड, डेटाबेस कॉन्फिगरेशन, साइट नाव, साइट ईमेल आणि प्रशासक क्रेडेन्शियल सेटिंग्ज निर्दिष्ट करणारा एक Drupal प्रोजेक्ट स्थापित करा.
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
