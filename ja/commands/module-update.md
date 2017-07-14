# module:update
コアやモジュールを更新

**application.gitbook.messages.usage:**
```
drupal module:update [arguments] [options]
moup
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--composer | Composerを使用してモジュールを更新
--simulate | Composerを使用して更新をシミュレーション

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | アップデートするモジュール名 (複数指定する場合はスペース区切り)。空の場合はComposerで管理されているコアおよび全てのモジュールが対象になります。
