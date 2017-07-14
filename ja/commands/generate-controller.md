# generate:controller
Generate & Register a controller

**application.gitbook.messages.usage:**
```
drupal generate:controller [options]
gcon
gcn
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | モジュール名
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | コンテナからサービスを読み込む
--test | Generate a test class
