# server
PHP मध्ये अंगभूत वेब सर्व्हर चालविते.

**वापर:**
```
drupal server [arguments]
serve
rs
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
address | पत्ता:पोर्ट मूल्य.

## उदाहरणे
* वापरून चालवा default address argument value 127.0.0.1:8088
```
drupal server
```
* वेगळ्या पोर्ट नंबरचा वापर करण्यासाठी पत्ता वितर्क पास करणे.
```
drupal server 127.0.0.1:8089
```
* चालवा default address argument values, using --root option to define the Drupal root
```
drupal --root=/var/www/drupal8.dev server
```
