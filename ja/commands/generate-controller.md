# generate:controller
Generate & Register a controller

**使い方:**
```
$ drupal generate:controller [options]
$ gcn  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--module | モジュール名
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | コンテナからサービスを読み込む
--test | Generate a test class
