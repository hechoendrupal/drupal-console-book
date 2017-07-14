# create:comments
创建评论

**Usage:**
```
drupal create:comments [arguments] [options]
crc
```

## Available options
Option | Details
-------|-------------
--limit | 创建评论数量
--title-words | 评论标题中的最大单词数量
--time-range | 评论的创建时间区间

## Available arguments
Argument | Details
---------|-------------
node-id | 创建评论的节点 ID

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
