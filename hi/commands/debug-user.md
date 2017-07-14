# debug:user
एप्लीकेशन के लिए करंट यूजरस को प्रदर्शित करता है

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | Filters the result list by uids [between quotes separated by spaces]
--username | Filters the result list by usernames [between quotes separated by spaces]
--mail | Filters the result list by user's e-mail [between quotes separated by spaces]
--roles | रोल्स से फिल्टर डिबग
--limit | डिबग में आप कितने यूजरस के सूचीबद्ध में होंगे

## Examples
* Users list on the site
```
drupal debug:user
```
