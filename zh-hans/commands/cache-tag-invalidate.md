# cache:tag:invalidate
Invalidate cache tags.

**使用方法:**
```
drupal cache:tag:invalidate [arguments]
cti
```

## 可用参数
参数 | 详细信息
---------|-------------
tag | One or more tags to invalidate.

## 例子
* Invalidate routes
```
drupal cti routes
```
* Invalidate a specific node
```
drupal cti node:1 node_list
```
