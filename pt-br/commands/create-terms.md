# create:terms
Create dummy terms for your Drupal 8 application.

**Utilização:**
```
drupal create:terms [arguments] [options]
crt
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--limit | How many terms would you like to create
--name-words | Maximum number of words in term names

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
vocabularies | Vocabularie(s) to be used in terms creation

## Exemplos
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
