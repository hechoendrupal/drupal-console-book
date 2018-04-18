# create:comments
为您的 Drupal 8 应用程序创建评论。

**使用方法:**
```
drupal create:comments [arguments] [options]
crc
```

## 可用选项
选项 | 详细信息
-------|-------------
--limit | 您想要创建多少条评论
--title-words | 评论标题中的最大单词数量
--time-range | 评论的创建时间范围

## 可用参数
参数 | 详细信息
---------|-------------
node-id | 创建评论依附的节点 ID

## 例子
* 提供生成评论的节点 ID。
```
drupal create:comments node-id
```
* 提供生成的评论数量，最大标题字和时间范围。
```
drupal create:comments node-id \
  --limit="2" \
  --title-words="5" \
  --time-range="1"
```
