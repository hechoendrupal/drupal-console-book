# create:users
Tạo dummy users cho ứng dụng Drupal 8 của bạn.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Bạn muốn tạo bao nhiêu user?
--password | Password to be set to users created
--time-range | How far back in time should the users be dated

## Available arguments
Argument | Details
---------|-------------
roles | Role(s) được sử dụng trong user creation

## Examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
