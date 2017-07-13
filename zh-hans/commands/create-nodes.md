# create:nodes
生成节点

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:nodes [arguments] [options]
$ crn  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | 生成多少个节点
--title-words | 节点标题允许的最多单词数量
--time-range | 节点的创建时间范围
--language | commands.create.nodes.options.language

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
content-types | 节点的内容类型(s)

## commands.generate.doc.gitbook.messages.examples
* Provide the content type name.
```
$ drupal create:nodes content-name
```
* Provide the limit of publications, limit of title words, time range and language.
```
$ drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"

```
