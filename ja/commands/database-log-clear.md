# database:log:clear
DbLogからイベントを削除する

**使い方:**
```
$ drupal database:log:clear [arguments] [options]
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--type | イベントを特定のタイプでフィルタする
--severity | イベントを特定の重要度のレベルでフィルタする
--user-id | イベントを特定のユーザーIDでフィルタする

## 利用可能な引数
引数 | 詳細
---------|-------------
event-id | DBLogのイベントID
