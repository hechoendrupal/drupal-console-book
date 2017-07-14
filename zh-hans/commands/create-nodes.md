# create:nodes
生成节点

**Usage:**
```
drupal create:nodes [arguments] [options]
crn
```

## Available options
Option | Details
-------|-------------
--limit | 生成多少个节点
--title-words | 节点标题允许的最多单词数量
--time-range | 节点的创建时间范围
--language | commands.create.nodes.options.language

## Available arguments
Argument | Details
---------|-------------
content-types | 节点的内容类型(s)

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
