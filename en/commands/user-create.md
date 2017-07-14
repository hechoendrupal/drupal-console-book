# user:create
Create users for the application

**Usage:**
```
drupal user:create [arguments] [options]
uc
```

## Available options
Option | Details
-------|-------------
--roles | User roles
--email | User email
--status | User status

## Available arguments
Argument | Details
---------|-------------
username | User name to be created
password | User password

## Examples
* Create user specifying username, password, role, email and status
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* Create admin user specifying username, password, role, email and status
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
