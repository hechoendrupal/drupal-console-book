# create:terms
ダミーのタームを作成

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | 作成するタームの数
--name-words | タームの名前に設定するの単語の最大数

## Available arguments
Argument | Details
---------|-------------
vocabularies | 作成するタームのボキャブラリー (複数指定可)

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
