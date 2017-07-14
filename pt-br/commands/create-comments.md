# create:comments
Criar comentários dummy para sua aplicação Drupal 8.

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | Quantos comentários você gostaria de criar.
--title-words | Número máximo de palavras em um título de comentário.
--time-range | Quão longe no tempo devem ser as datas dos comentários.

## Available arguments
Argument | Details
---------|-------------
node-id | Node ID onde os comentários serão criados

## Examples
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
