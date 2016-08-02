# migrate:execute
Execute a migration available for application

**使い方:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--site-url | Site Source URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | Database Host
--db-name | Database Name
--db-user | Database User
--db-pass | Database Pass
--db-prefix | Database Prefix
--db-port | Database Port
--exclude | Migration id(s) to exclude

## 利用可能な引数
引数 | 詳細
---------|-------------
migration-ids | Migration id(s)
