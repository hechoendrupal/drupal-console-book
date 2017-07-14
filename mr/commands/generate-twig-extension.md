# generate:twig:extension
एक ट्विंग विस्तार उत्पन्न करा.

**Usage:**
```
drupal generate:twig:extension [options]
gte
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--name | विस्तारीत विस्तार नाव.
--class | वर्ग नाव.
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
