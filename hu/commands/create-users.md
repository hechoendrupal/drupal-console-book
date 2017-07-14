# create:users
Tesztfelhasználók létrehozása egy Drupal 8 alkalmazáshoz.

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | Hány felhasználó jöjjön létre
--password | A létrehozott felhasználókhoz beállított jelszó
--time-range | Mennyire legyen visszadátumozva a felhasználók létrehozása

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | A felhasználók létrehozásakor használandó szerepkörök

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
