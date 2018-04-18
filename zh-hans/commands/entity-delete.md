# entity:delete
Delete an specific entity

**使用方法:**
```
drupal entity:delete [arguments] [options]
ed
```

## 可用选项
选项 | 详细信息
-------|-------------
--all | Delete all entities of the given type.

## 可用参数
参数 | 详细信息
---------|-------------
entity-definition-id | Entity definition id
entity-id | Entity ID to be deleted

## 例子
* Delete entity type content using node id
```
drupal entity:delete node 1
```
