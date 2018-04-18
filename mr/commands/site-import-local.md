# site:import:local
अस्तित्वातील स्थानिक Drupal प्रोजेक्ट आयात/कॉन्फिगर करा.

**वापर:**
```
drupal site:import:local [arguments] [options]
sil
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--environment | पर्यावरणाचे नाव जे आयात केले जाणार आहे.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
name | साइट कॉन्फिगर तयार करण्यासाठी वापरला जाणार असलेले नाव.
directory | विद्यमान Drupal रूट निर्देशिका.

## उदाहरणे
* साइट नाव आणि पथ निर्दिष्ट स्थानिक ड्रायव्हल प्रकल्प आयात करा.
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
