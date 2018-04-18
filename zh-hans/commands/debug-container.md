# debug:container
显示应用程序的当前服务。

**使用方法:**
```
drupal debug:container [arguments] [options]
dco
cod
```

## 可用选项
选项 | 详细信息
-------|-------------
--parameters | 服务名称
--tag | Service tag 

## 可用参数
参数 | 详细信息
---------|-------------
service | 服务名称
method | 方法名称
arguments | CSV 或 JSON 格式的参数数组。

## 例子
* 显示 views.views_data_helper 服务
```
drupal debug:container views.views_data_helper
```
