# create:vocabularies
ダミーのボキャブラリーを追加

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | 作成するボキャブラリーの数
--name-words | ボキャブラリーの名前に設定するの単語の最大数

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
