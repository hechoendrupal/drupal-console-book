# debug:database:table
データベース内の全てのテーブルを表示

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | settings.phpのデータベースのキー

## Available arguments
Argument | Details
---------|-------------
table | デバッグするテーブル

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
