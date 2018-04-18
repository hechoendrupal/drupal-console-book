# user:create
Create users for the application

**Utilização:**
```
drupal user:create [arguments] [options]
uc
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--roles | User roles
--email | User email
--status | User status

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
username | User name to be created
password | User password

## Exemplos
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
