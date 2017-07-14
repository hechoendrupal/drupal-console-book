# create:users
ダミーのユーザーを作成

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | 作成するユーザーの数
--password | 作成したユーザーのパスワード
--time-range | ユーザーの作成時刻

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | 作成するユーザーのロール (複数指定可)

## application.gitbook.messages.examples
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
