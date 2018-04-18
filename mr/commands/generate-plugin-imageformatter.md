# generate:plugin:imageformatter
प्रतिमा फॉर्मेटर प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:imageformatter [options]
gpif
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.

## उदाहरणे
* मॉड्यूलचे नाव, वर्ग, त्याचे लेबल आणि प्लगिनआयडीनिर्दिष्ट करणारा एक प्रतिमा फॉर्मेटर प्लगइन उत्पन्न करा.
```
drupal generate:plugin:imageformatter  \
  --module="modulename"  \
  --class="ExampleImageFormatter"  \
  --label="Example image formatter"  \
  --plugin-id="example_image_formatter"
```
