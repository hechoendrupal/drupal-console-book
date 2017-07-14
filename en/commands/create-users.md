# create:users
Create dummy users for your Drupal 8 application.

**Usage:**
```
drupal create:users [arguments] [options]
cru
```

## Available options
Option | Details
-------|-------------
--limit | How many users would you like to create
--password | Password to be set to users created
--time-range | How far back in time should the users be dated

## Available arguments
Argument | Details
---------|-------------
roles | Role(s) to be used in user creation

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
