# user:role
添加/移除给定用户的角色

**使用方法:**
```
drupal user:role [arguments]
ur
```

## 可用参数
参数 | 详细信息
---------|-------------
operation | 添加或移除
user | 用户(仅限一个)
role | 添加或移除的角色. 请提供机读名称 (仅限一个)

## 例子
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
