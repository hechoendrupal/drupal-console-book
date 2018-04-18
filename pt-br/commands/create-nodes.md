# create:nodes
Create dummy nodes for your Drupal 8 application.

**Utilização:**
```
drupal create:nodes [arguments] [options]
crn
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--limit | How many nodes would you like to create
--title-words | Maximum number of words in node titles
--time-range | How far back in time should the nodes be dated
--language | commands.create.nodes.options.language

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
content-types | Content type(s) to be used in node creation

## Exemplos
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
