# generate:update
生成一个 hook_update_N() 的实现

**使用方法:**
```
drupal generate:update [options]
gu
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--update-n | 更新数字

## 例子
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
