# generate:update
生成一个 hook_update_N() 的实现

**Usage:**
```
drupal generate:update [options]
gu
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--update-n | 更新数字

## Examples
* Generate an update N hook implementation specifying the module name and the N value
```
drupal generate:update  \
  --module="modulename"  \
  --update-n="8001"
```
