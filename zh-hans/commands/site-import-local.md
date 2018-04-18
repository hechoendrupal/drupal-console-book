# site:import:local
导入/配置一个已经存在的 Drupal 项目

**使用方法:**
```
drupal site:import:local [arguments] [options]
sil
```

## 可用选项
选项 | 详细信息
-------|-------------
--environment | 将要导入的环境名称

## 可用参数
参数 | 详细信息
---------|-------------
name | 用于生成站点配置的名称
directory | 已存在网站 Drupal 根文件夹

## 例子
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
