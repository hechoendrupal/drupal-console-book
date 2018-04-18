# config:diff
比对目录，输出与活动配置不同的配置项。

**使用方法:**
```
drupal config:diff [arguments] [options]
cdi
```

## 可用选项
选项 | 详细信息
-------|-------------
--reverse | 反向查看变化（比如，比对目录与活动配置的差异）。

## 可用参数
参数 | 详细信息
---------|-------------
directory | 对比的目录。如果省略，则从 Drupal 配置目录中进行选择。

## 例子
* 提供一个配置目录
```
drupal config:diff ../config/path
```
