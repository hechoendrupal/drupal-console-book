# generate:command
कन्सोलसाठी आदेश उत्पन्न करा.

**वापर:**
```
drupal generate:command [options]
gco
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--extension | विस्तार नाव.
--extension-type | विस्तार प्रकार.
--class | आज्ञा वर्णन करणारा वर्ग (' कमांड ' शब्दासह समाप्त होणे आवश्यक आहे).
--name | कमांडचे नाव.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | आज्ञावली अधिकृत करताना डीवोल साइट स्थापनेची जाणीव आहे.
--services | कंटेनर मधून सेवा भरा.
--generator | Add a Generator class for this command.

## उदाहरणे
* विस्तार नाव आणि प्रकार, त्याचे वर्ग आणि नाव निर्दिष्ट करणारा आदेश उत्पन्न करा.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
