# config:export:single
导出单个配置

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:export:single [options]
$ ces  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--name | commands.config.export.single.options.name
--directory | 导出配置存放目录
--module | 模块名称
--include-dependencies | 同时输出其他相关配置.
--optional | Export config as an optional YAML configuration in your module
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## commands.generate.doc.gitbook.messages.examples
* Provide config settings name to be exported
```
$ drupal config:export:single \
  --name=config.settings.name
```
* if uuid and/or config hashes will be removed.
```
$ drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash

```
