# user:create
Create users for the application

**使用方法:**
```
drupal user:create [arguments] [options]
uc
```

## 可用选项
选项 | 详细信息
-------|-------------
--roles | User roles
--email | User email
--status | User status

## 可用参数
参数 | 详细信息
---------|-------------
username | User name to be created
password | User password

## 例子
* Create user specifying username, password, role, email and status
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* Create admin user specifying username, password, role, email and status
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
