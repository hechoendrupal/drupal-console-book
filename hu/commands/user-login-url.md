# user:login:url
Egyszer használatos felhasználói bejelentkezési URL-címet ad vissza.

**Usage:**
```
drupal user:login:url [arguments]
ulu
usli
uli
```

## Available arguments
Argument | Details
---------|-------------
user | User name/id.

## Examples
* Get one time login url for user id 1
```
drupal user:login:url  1
```
* Get one time login url for username jmolivas
```
drupal user:login:url jmolivas
```
