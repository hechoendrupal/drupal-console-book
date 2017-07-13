# migrate:execute
执行可用迁移

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal migrate:execute [arguments] [options]
$ mie  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--site-url | 来源网站 URL
--db-type | commands.migrate.setup.migrations.options.db-type
--db-host | 数据库主机
--db-name | 数据库名称
--db-user | 数据库用户
--db-pass | 数据库密码
--db-prefix | 数据库前缀
--db-port | 数据库端口
--exclude | 被排除的迁移 ID
--source-base_path | commands.migrate.execute.options.source-base-path

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
migration-ids | 一个或多个迁移 ID
