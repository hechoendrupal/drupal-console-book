# create:users
Tesztfelhasználók létrehozása egy Drupal 8 alkalmazáshoz.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal create:users [arguments] [options]
$ cru  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--limit | Hány felhasználó jöjjön létre
--password | A létrehozott felhasználókhoz beállított jelszó
--time-range | Mennyire legyen visszadátumozva a felhasználók létrehozása

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
roles | A felhasználók létrehozásakor használandó szerepkörök

## commands.generate.doc.gitbook.messages.examples
* Provide the user role.
```
$ drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
$ drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"

```
