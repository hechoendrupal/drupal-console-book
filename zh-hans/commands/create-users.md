# create:users
为您的 Drupal 8 应用程序创建用户。

**使用方法:**
```
drupal create:users [arguments] [options]
cru
```

## 可用选项
选项 | 详细信息
-------|-------------
--limit | 您要创建多少用户？
--password | 设置创建用户时用户的密码
--time-range | 设置创建用户的时间

## 可用参数
参数 | 详细信息
---------|-------------
roles | 创建用户时使用的角色

## 例子
* 提供用户角色。
```
drupal create:users role
```
* 提供创建用户的数量，密码和创建时间范围。
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
