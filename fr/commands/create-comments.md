# create:comments
Créé des commentaires factices pour votre application Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:comments [arguments] [options]
crc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Nombre de commentaires à créer
--title-words | Le nombre maximum de mots dans les titres des commentaire.
--time-range | A partir de quelle date les commentaires doivent être générés ?

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
node-id | L'ID du noeud où les commentaires vont être créés.

## application.gitbook.messages.examples
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
