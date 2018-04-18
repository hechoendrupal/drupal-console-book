# create:terms
为您的 Drupal 8 应用程序创建术语。

**使用方法:**
```
drupal create:terms [arguments] [options]
crt
```

## 可用选项
选项 | 详细信息
-------|-------------
--limit | 您要创建多少个术语？
--name-words | 术语名称中单词的最多数量

## 可用参数
参数 | 详细信息
---------|-------------
vocabularies | 用于创建术语的词汇表

## 例子
* 提供词汇表术语名称。
```
drupal create:terms vocabulary
```
* 提供添加术语和标题用词的限制条件。
```
drupal create:terms tags \
  --limit="10" \
  --name-words="5"
```
