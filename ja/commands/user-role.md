# user:role
ユーザーの役割を追加・削除する

**Usage:**
```
drupal user:role [arguments]
ur
```

## Available arguments
Argument | Details
---------|-------------
operation | 追加または削除
user | 対象となるユーザー (1ユーザーのみ)
role | 追加・削除する役割。システム内部名称で1つだけ指定してください。

## Examples
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
