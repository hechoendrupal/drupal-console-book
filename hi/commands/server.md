# server
PHP निर्मित वेब सर्वर चलायॆ

**Usage:**
```
drupal server [arguments]
serve
rs
```

## Available arguments
Argument | Details
---------|-------------
address | पता: पोर्ट मान

## Examples
* डिफ़ॉल्ट पता तर्क मूल्य का उपयोग करे 127.0.0.1:8088
```
Drupal सर्वर
```
* पासिंग पता तर्क एक अलग पोर्ट नंबर का उपयोग करने के लिए
```
drupal सर्वर 127.0.0.1:8089
```
* डिफ़ॉल्ट पता तर्क मूल्यों चल रहा हे --root विकल्प का उपयोग Drupal के जड़ को परिभाषित करने के लिए
```
drupal --root=/var/www/drupal8.dev सर्वर
```
