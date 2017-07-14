# create:nodes
Créer des nœuds factices pour votre application Drupal 8.

**application.gitbook.messages.usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Combien de nœuds voulez-vous générer
--title-words | Nombre de mots maximum des titres
--time-range | De combien de temps au maximum doivent dater les nœuds générés
--language | commands.create.nodes.options.language

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-types | Le(s) type(s) de contentu à utiliser pour la création de nœuds

## application.gitbook.messages.examples
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
