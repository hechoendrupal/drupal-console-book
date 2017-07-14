# create:vocabularies
Génère des vocabulaires factices pour votre application Drupal

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | Nombre de vocabulaires à créer
--name-words | Nombre maximum de mots des vocabulaires

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
