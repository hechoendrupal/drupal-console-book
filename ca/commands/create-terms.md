# create:terms
Crear termes 'dummy' per l'aplicació Drupal 8.

**Ús:**
```
drupal create:terms [arguments] [options]
crt
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--limit | Quants termes voldrieu crear
--name-words | Màxim de paraules dels noms del termes

## Arguments disponibles
Argument | Detalls
---------|-------------
vocabularies | Vocabulari utilitzat en la creació termes

## Exemples
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
