# generate:plugin:skeleton
त्या प्लगिनसाठी स्केप्लेट प्लगइनची अंमलबजावणी उत्पन्न करा Drupal Console मध्ये विशिष्ट जनरेटर नाही.

**Usage:**
```
drupal generate:plugin:skeleton [options]
gps
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--plugin-id | commands.generate.plugin.options.plugin-id
--class | प्लगइन वर्ग नाव
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate a plugin skeleton specifying module name, the plugin id and the class
```
drupal generate:plugin:skeleton  \
  --module="modulename"  \
  --plugin-id="link_relation_type"  \
  --class="DefaultLinkRelationType"
```
