# config:import:single
निवडलेले कॉन्फिगरेशन आयात करा.

**application.gitbook.messages.usage:**
```
drupal config:import:single [options]
cis
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--file | आयात करण्यासाठी फाईल (ली) नावाची किंवा फाईल (फां) पूर्ण पथ.
--directory | आयात करण्यासाठी कॉन्फिगरेशनच्या निर्देशिकेत मार्ग.

## application.gitbook.messages.examples
* पूर्ण मार्ग वापरून फाइल पर्याय प्रदान करणे.
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* फाइल आणि निर्देशिका पर्याय प्रदान.
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```
