# config:import:single
Import the selected configuration.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:import:single [options]
$ cis  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--file | The file(s) name or file(s) absolute path to import
--directory | कॉन्फ़िगरेशन की एक डायरेक्टरी के लिए पथ इम्पोर्ट करते हैं।

## commands.generate.doc.gitbook.messages.examples
* Providing a file option using full path.
```
$ drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* Providing file and directory options
```
$ drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"

```
