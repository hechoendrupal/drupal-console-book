# debug:config
現在の設定を表示する

**application.gitbook.messages.usage:**
```
drupal debug:config [arguments]
dc
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | 設定の名前

## application.gitbook.messages.examples
* List all configuration object names.
```
drupal config:debug
```
* Display system site configurations values.
```
drupal config:debug system.site
```
* List all system configuration names.
```
drupal config:debug | grep system
```
