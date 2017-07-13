# config:override
覆写活动配置

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:override [arguments]
$ co  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | 配置名称
key | 键
value | 值

## commands.generate.doc.gitbook.messages.examples
* 设置 Contact 模块 flood limit 为 10.
```
$ drupal config:override contact.settings flood.limit 10
```
