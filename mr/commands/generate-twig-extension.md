# generate:twig:extension
एक ट्विंग विस्तार उत्पन्न करा.

**वापर:**
```
drupal generate:twig:extension [options]
gte
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--name | विस्तारीत विस्तार नाव.
--class | वर्ग नाव.
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्युलचे नाव, विस्तार नाव आणि त्याचे वर्ग हे निर्दिष्ट करणारा एक डुलक विस्तारीत उत्पन्न करा.
```
drupal generate:twig:extension  \
  --module="modulename"  \
  --name="modulename.twig.extension"  \
  --class="DefaultTwigExtension"
```
