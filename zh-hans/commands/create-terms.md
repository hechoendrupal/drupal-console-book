# create:terms
生成分类术语

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:terms [arguments] [options]
$ crt  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | 生成多少个分类术语
--name-words | 分类术语名称允许的最多单词数量

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
vocabularies | 用于生成分类术语的词汇表(s)

## commands.generate.doc.gitbook.messages.examples
* Provide the vocabulary term name.
```
$ drupal create:terms vocabulary
```
* Provide the limit of terms to add and limit of title words.
```
$ drupal create:terms tags \
  --limit="10" \
  --name-words="5"

```
