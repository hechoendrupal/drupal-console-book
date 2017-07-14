# node:access:rebuild
ノードのアクセス権限を再構築します。全てのコンテンツに対する権限設定を削除し、現在のモジュールおよび設定で置き換えます。

**Usage:**
```
drupal node:access:rebuild [options]
nar
```

## Available options
Option | Details
-------|-------------
--batch | バッチモードで処理する

## Examples
* ノードのアクセス権限を再構築
```
drupal node:access:rebuild --batch
```
