# create:nodes
Créer des nœuds factices pour votre application Drupal 8.

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | Combien de nœuds voulez-vous générer
--title-words | Nombre de mots maximum des titres
--time-range | De combien de temps au maximum doivent dater les nœuds générés
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | Le(s) type(s) de contentu à utiliser pour la création de nœuds

## Examples
* Provide the content type name.
```
drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
