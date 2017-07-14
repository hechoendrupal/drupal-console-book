# user:create
Create users for the application

**application.gitbook.messages.usage:**
```
drupal user:create [arguments] [options]
uc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--roles | User roles
--email | User email
--status | User status

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
username | User name to be created
password | User password

## application.gitbook.messages.examples
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
