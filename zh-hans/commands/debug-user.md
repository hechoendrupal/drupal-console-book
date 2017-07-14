# debug:user
显示网站的当前用户(s)

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | 使用用户ID过滤 [使用空格进行间隔, 值包含空格两边加引号]
--username | 使用用户名过滤 [使用空格进行间隔, 值包含空格两边加引号]
--mail | 使用用户邮件地址过滤 [使用空格进行间隔, 值包含空格两边加引号]
--roles | 用于过滤用户的角色
--limit | 指定显示的用户数量

## Examples
* Users list on the site
```
drupal debug:user
```
