# generate:command
कन्सोलसाठी आदेश उत्पन्न करा.

**Usage:**
```
drupal generate:command [options]
gco
gcm
```

## Available options
Option | Details
-------|-------------
--extension | विस्तार नाव.
--extension-type | विस्तार प्रकार.
--class | आज्ञा वर्णन करणारा वर्ग (' कमांड ' शब्दासह समाप्त होणे आवश्यक आहे).
--name | कमांडचे नाव.
--container-aware | आज्ञावली अधिकृत करताना डीवोल साइट स्थापनेची जाणीव आहे.
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
