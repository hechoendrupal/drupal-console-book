# config:import:single
निवडलेले कॉन्फिगरेशन आयात करा.

**Usage:**
```
drupal config:import:single [options]
cis
```

## Available options
Option | Details
-------|-------------
--file | आयात करण्यासाठी फाईल (ली) नावाची किंवा फाईल (फां) पूर्ण पथ.
--directory | commands.config.import.arguments.directory

## Examples
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
