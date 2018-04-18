# create:vocabularies
Create dummy vocabularies for your Drupal 8 application.

**Utilização:**
```
drupal create:vocabularies [options]
crv
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--limit | How many vocabularies would you like to create
--name-words | Maximum number of words in vocabulary names

## Exemplos
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
