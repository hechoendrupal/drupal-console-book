# create:vocabularies
为您的 Drupal 8 应用程序创建词汇表。

**使用方法:**
```
drupal create:vocabularies [options]
crv
```

## 可用选项
选项 | 详细信息
-------|-------------
--limit | 你想创建多少个词汇表
--name-words | 词汇表名称中的最大单词数量

## 例子
* 提供创建词汇表的数量和词汇表名称中的最大单词数量
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
