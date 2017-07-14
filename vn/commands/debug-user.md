# debug:user
Hiển thị các người dùng hiện tại cho ứng dụng

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | Filters the result list by uids [between quotes separated by spaces]
--username | Filters the result list by usernames [between quotes separated by spaces]
--mail | Filters the result list by user's e-mail [between quotes separated by spaces]
--roles | Các vai trò để lọc debug
--limit | Bạn muốn liệt kê bao nhiêu người dùng trong debug

## Examples
* Users list on the site
```
drupal debug:user
```
