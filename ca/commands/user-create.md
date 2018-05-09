# user:create
Create users for the application

**Ús:**
```
drupal user:create [arguments] [options]
uc
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--roles | User roles
--email | User email
--status | User status

## Arguments disponibles
Argument | Detalls
---------|-------------
username | User name to be created
password | User password

## Exemples
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
