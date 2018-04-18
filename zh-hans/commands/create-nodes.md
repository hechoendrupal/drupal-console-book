# create:nodes
为您的 Drupal 8 应用程序创建节点。

**使用方法:**
```
drupal create:nodes [arguments] [options]
crn
```

## 可用选项
选项 | 详细信息
-------|-------------
--limit | 您要创建多少个节点
--title-words | 节点标题中的最大单词数量
--time-range | 节点的创建时间范围
--language | commands.create.nodes.options.language

## 可用参数
参数 | 详细信息
---------|-------------
content-types | 在节点创建时使用的内容类型

## 例子
* 提供内容类型名称。
```
drupal create:nodes content-name
```
* 提供发布的限制，标题单词数量、创建时间范围和语言的限制。
```
drupal create:nodes content-name \
  --limit="5" \
  --title-words="5" \
  --time-range="1" \
  --language="und"
```
