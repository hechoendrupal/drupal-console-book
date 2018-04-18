# user:password:reset
为指定用户重设密码.

**使用方法:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## 可用参数
参数 | 详细信息
---------|-------------
user | User name/id
password | 文本格式的密码

## 例子
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
