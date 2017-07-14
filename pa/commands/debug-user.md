# debug:user
Displays current users for the application

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
--roles | Roles to filter debug
--limit | How many users would you like to be listed in debug

## Examples
* Users list on the site
```
drupal debug:user
```
