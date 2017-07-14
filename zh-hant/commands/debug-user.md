# debug:user
顯示目前網站應用中的使用者

**Usage:**
```
drupal debug:user [options]
dus
```

## Available options
Option | Details
-------|-------------
--uid | 以逗點(,)區隔 uid ，以篩選要顯示的使用者列表，例如："1,2,3"
--username | 以逗點(,)區隔使用者名稱，以篩選要顯示的使用者列表，例如："amo, chris"
--mail | 以逗點(,)區隔使用者 Email， 以篩選要顯示的使用者列表，例如："user@example.com, user2@example.com"
--roles | 要在偵錯列表中顯示的角色
--limit | 要在偵錯列表中顯示的使用者數量上限

## Examples
* Users list on the site
```
drupal debug:user
```
