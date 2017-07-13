# config:export:view
导出视图

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | 模块名称
--optional-config | 导出视图作为模块的可选配置
--include-module-dependencies | 在模块的 info 文件中包含相关依赖模块

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
view-id | 视图 ID

## commands.generate.doc.gitbook.messages.examples
* Provide a view id
```
$ drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
$ drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies

```
