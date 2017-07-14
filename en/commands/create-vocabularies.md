# create:vocabularies
Create dummy vocabularies for your Drupal 8 application.

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | How many vocabularies would you like to create
--name-words | Maximum number of words in vocabulary names

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
