# config:export:content:type
एक विशिष्ट कंटेंट टाइप और अपने फ़ील्ड्स में एक्सपोर्ट करें।

**Usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | अपने मॉड्यूल में एक वैकल्पिक YAML कॉन्फ़िगरेशन के रूप में कंटेंट टाइप एक्सपोर्ट करे
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Available arguments
Argument | Details
---------|-------------
content-type | कंटेंट टाइप एक्सपोर्ट किए जाये

## Examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
