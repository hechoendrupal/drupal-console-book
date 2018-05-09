# create:terms
Génère des termes de taxonomie factices pour votre application Drupal 8.

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | Combien de termes voulez-vous générer
--name-words | Nombre maximums de mots des noms des termes

## Available arguments
Argument | Details
---------|-------------
vocabularies | Vocabulaire(s) à utiliser lors de la génération des termes

## Examples
* Provide the vocabulary term name.
```
drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
