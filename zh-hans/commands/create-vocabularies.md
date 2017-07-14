# create:vocabularies
生成词汇表

**Usage:**
```
drupal create:vocabularies [options]
crv
```

## Available options
Option | Details
-------|-------------
--limit | 生成多少个词汇表
--name-words | 词汇表名称允许的最多单词数量

## Examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
