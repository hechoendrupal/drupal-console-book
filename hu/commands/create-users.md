# create:users
Tesztfelhasználók létrehozása egy Drupal 8 alkalmazáshoz.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | Hány felhasználó jöjjön létre
--password | A létrehozott felhasználókhoz beállított jelszó
--time-range | Mennyire legyen visszadátumozva a felhasználók létrehozása

## Available arguments
Argument | Details
---------|-------------
roles | A felhasználók létrehozásakor használandó szerepkörök

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
