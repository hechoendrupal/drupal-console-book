# debug:container
अनुप्रयोग चालू सेवा दाखवा.

**वापर:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--parameters | सेवेचे नाव.
--tag | Service tag 

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
service | सेवेचे नाव.
method | पद्धत नाव
arguments | CSV किंवा JSON स्वरूपातील वितर्कांचा अॅरे.

## उदाहरणे
* views.views_data_helper सेवा दर्शवितो.
```
drupal debug:container views.views_data_helper
```
