# migrate:execute
执行可用迁移

**使用方法:**
```
drupal migrate:execute [arguments] [options]
mie
```

## 可用选项
选项 | 详细信息
-------|-------------
--site-url | 来源网站 URL
--db-type | commands.migrate.execute.migrations.options.db-type
--db-host | 数据库主机
--db-name | 数据库名称
--db-user | 数据库用户
--db-pass | 数据库密码
--db-prefix | 数据库前缀
--db-port | 数据库端口
--exclude | 被排除的迁移 ID
--source-base_path | Local file directory containing your source site (e.g. /var/www/docroot), or your site address (for example http://example.com)

## 可用参数
参数 | 详细信息
---------|-------------
migration-ids | 一个或多个迁移 ID
