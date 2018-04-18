# multisite:new
建立一个新的多站点安装文件(s)

**使用方法:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## 可用选项
选项 | 详细信息
-------|-------------
--copy-default | Copies existing site from the default install.

## 可用参数
参数 | 详细信息
---------|-------------
directory | Name of directory under 'sites' which should be created.
uri | Site URI to add to sites.php.

## 例子
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
