# node:access:rebuild
ノードのアクセス権限を再構築します。全てのコンテンツに対する権限設定を削除し、現在のモジュールおよび設定で置き換えます。

**application.gitbook.messages.usage:**
```
drupal node:access:rebuild [options]
nar
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--batch | バッチモードで処理する

## application.gitbook.messages.examples
* ノードのアクセス権限を再構築
```
drupal node:access:rebuild --batch
```
