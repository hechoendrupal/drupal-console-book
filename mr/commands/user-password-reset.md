# user:password:reset
एका विशिष्ट वापरकर्त्यासाठी संकेतशब्द रीसेट करा.

**वापर:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
user | User name/id
password | मजकूर स्वरूपात संकेतशब्द

## उदाहरणे
* संकेतशब्द आणि वापरकर्ता आयडी आणि नवीन पासवर्ड निर्दिष्ट संकेतशब्द अद्ययावत करा.
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
