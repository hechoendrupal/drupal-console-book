# database:log:clear
DBLog सारणीतून कार्यक्रम काढा, फिल्टर उपलब्ध आहेत.

**वापर:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
event-id | DBLog इव्हेंट आयडी.

## उदाहरणे
* DBLog सारणीतून डेटाबेस लॉग साफ करा.
```
drupal database:log:clear \
  <database>
```
* फिल्टरचा वापर करून DBLog सारणीतून डेटाबेस लॉग साफ करा.
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
