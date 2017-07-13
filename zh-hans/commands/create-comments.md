# create:comments
创建评论

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:comments [arguments] [options]
$ crc  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | 创建评论数量
--title-words | 评论标题中的最大单词数量
--time-range | 评论的创建时间区间

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
node-id | 创建评论的节点 ID

## commands.generate.doc.gitbook.messages.examples
* Provide the node id where the comments will be generated.
```
$ drupal create:comments  node-id
```
* Provide number of comments to generate, max title words and time range.
```
$ drupal create:comments  node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"

```
