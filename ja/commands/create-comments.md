# create:comments
ダミーのコメントを作成

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | 作成するコメントの数
--title-words | コメントのタイトルに設定する単語の最大数
--time-range | コメントの作成時刻

## Available arguments
Argument | Details
---------|-------------
node-id | コメントを作成するノードのID

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
