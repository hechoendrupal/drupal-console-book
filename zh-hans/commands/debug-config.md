# debug:config
列出配置对象名称和单个配置对象。

**使用方法:**
```
drupal debug:config [arguments] [options]
dc
```

## 可用选项
选项 | 详细信息
-------|-------------
--show-overridden | Show overridden configurations.

## 可用参数
参数 | 详细信息
---------|-------------
name | 配置对象名称，例如 "system.site"。

## 例子
* 列出所有配置对象名称。
```
drupal config:debug
```
* 显示系统的站点配置值。
```
drupal config:debug system.site
```
* 列出所有系统配置名称。
```
drupal config:debug | grep system
```
* List all configuration including overridden values.
```
drupal debug:config --show-overridden
```
