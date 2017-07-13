# debug:config
显示当前配置

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:config [arguments]
$ dc  
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
name | 配置名称

## commands.generate.doc.gitbook.messages.examples
* List all configuration object names.
```
$ drupal config:debug
```
* Display system site configurations values.
```
$ drupal config:debug system.site
```
* List all system configuration names.
```
$ drupal config:debug | grep system
```
