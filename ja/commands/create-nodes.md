# create:nodes
ダミーのノードを作成

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | 作成するノードの数
--title-words | タイトルに設定するの単語の最大数
--time-range | ノードの作成時刻
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | 作成するノードのコンテンツタイプ (複数指定可)

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
