# config:diff
输出选取目录中和使用中不同的配置项目.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:diff [arguments] [options]
$ cdi  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--reverse | 反向显示差异(就是说：从一个目录到使用配置的比较).

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
directory | 要对比的目录. 缺省使用配置目录.

## commands.generate.doc.gitbook.messages.examples
* Provide a config directory
```
$ drupal config:diff ../config/path
```
