# generate:twig:extension
Generate a Twig extension.

**Usage:**
```
drupal generate:twig:extension [options]
gte
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--name | Twig Extension name
--class | Class name
--services | सर्विसेज़ को container से लोड करें।

## Examples
* Generate a twig extension specifying the module name, the extension name and its class
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
