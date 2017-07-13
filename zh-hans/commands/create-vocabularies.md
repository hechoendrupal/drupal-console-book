# create:vocabularies
生成词汇表

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:vocabularies [options]
$ crv  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | 生成多少个词汇表
--name-words | 词汇表名称允许的最多单词数量

## commands.generate.doc.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
$ drupal create:vocabularies \
  --limit="5" \
  --name-words="5"

```
