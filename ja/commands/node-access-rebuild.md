# node:access:rebuild
ノードのアクセス権限を再構築します。全てのコンテンツに対する権限設定を削除し、現在のモジュールおよび設定で置き換えます。

**使い方:**
```
$ drupal node:access:rebuild [options]
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--batch | バッチモードで処理する

## 例
* ノードのアクセス権限を再構築
```
$ drupal node:access:rebuild --batch
```
