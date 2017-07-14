# database:log:clear
DBLog सारणीतून कार्यक्रम काढा, फिल्टर उपलब्ध आहेत.

**application.gitbook.messages.usage:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | DBLog इव्हेंट आयडी.

## application.gitbook.messages.examples
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
