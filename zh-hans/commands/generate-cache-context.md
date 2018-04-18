# generate:cache:context
Generate a cache context

**使用方法:**
```
drupal generate:cache:context [options]
gcc
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--cache-context | The cache context name
--class | Cache context class name
--services | 从容器加载服务。

## 例子
* Generate cache for a context specifying the module, the context name and its class
```
drupal generate:cache:context  \
  --module="modulename"  \
  --cache-context="ContextName"  \
  --class="DefaultCacheContext"
```
