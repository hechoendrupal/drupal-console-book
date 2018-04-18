# debug:database:table
दिलेल्या डेटाबेसमध्ये सर्व सारण्या दर्शवा.

**वापर:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--database | Settings.php पासून डेटाबेस की.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
table | टेबल डीबग करण्यासाठी.

## उदाहरणे
* डेटाबेसवर सर्व टेबल्स दर्शवा.
```
drupal debug:database:table
```
* वितर्क वर निर्दिष्ट केलेल्या नोड सारणीवर फील्ड दर्शवा किंवा दुसरे.
```
drupal debug:database:table node
```
