# create:vocabularies
Crear vocabulari 'dummy' per l'aplicació Drupal 8.

**Ús:**
```
drupal create:vocabularies [options]
crv
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--limit | Quants vocabularis voldrieu crear
--name-words | Màxim de paraules utilitzades al nom del vocabulari

## Exemples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
