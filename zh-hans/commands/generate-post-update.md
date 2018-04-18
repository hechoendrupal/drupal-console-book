# generate:post:update
生成一个 hook_post_update_NAME() 的实现

**使用方法:**
```
drupal generate:post:update [options]
gpu
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--post-update-name | Post Update 名称

## 例子
* Generate an implementation of post update hook specifying the module name and the post update name
```
drupal generate:post:update  \
  --module="modulename"  \
  --post-update-name="PostUpdateName"
```
