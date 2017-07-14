# create:terms
生成分类术语

**Usage:**
```
drupal create:terms [arguments] [options]
crt
```

## Available options
Option | Details
-------|-------------
--limit | 生成多少个分类术语
--name-words | 分类术语名称允许的最多单词数量

## Available arguments
Argument | Details
---------|-------------
vocabularies | 用于生成分类术语的词汇表(s)

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
