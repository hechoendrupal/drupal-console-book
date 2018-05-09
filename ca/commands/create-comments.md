# create:comments
Create dummy comments for your Drupal 8 application.

**Ús:**
```
drupal create:comments [arguments] [options]
crc
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--limit | How many comments would you like to create
--title-words | Maximum number of words in comment titles
--time-range | How far back in time should the comments be dated

## Arguments disponibles
Argument | Detalls
---------|-------------
node-id | Node ID where the comments will be created

## Exemples
* Provide the node id where the comments will be generated.
```
drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
