# generate:command
कंसोल के लिए कमाण्डो को उत्पन्न करें।

**Usage:**
```
drupal generate:command [options]
gco
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | कमाण्ड क्लास का नाम
--name | कमाण्ड का नाम।
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Drupal साइट स्थापना के बारे में कमांड पता है जब एक्सेक्युट होगा?
--services | सर्विसेज़ को container से लोड करें।
--generator | Add a Generator class for this command.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
