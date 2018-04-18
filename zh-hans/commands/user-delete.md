# user:delete
删除网站用户(s)

**使用方法:**
```
drupal user:delete [options]
ud
```

## 可用选项
选项 | 详细信息
-------|-------------
--user | User name/id to be deleted
--roles | 要删除用户的角色

## 例子
* Delete user specifying the id and the user role
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Delete user specifying its id
```
drupal user:delete  \
  --user-id="3"
```
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
