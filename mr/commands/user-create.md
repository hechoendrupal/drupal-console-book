# user:create
अनुप्रयोगासाठी वापरकर्ते तयार करा.

**Usage:**
```
drupal user:create [arguments] [options]
uc
```

## Available options
Option | Details
-------|-------------
--roles | वापरकर्ता भूमिका.
--email | वापरकर्ता ईमेल.
--status | वापरकर्ता स्थिती.

## Available arguments
Argument | Details
---------|-------------
username | वापरकर्ता नाव तयार करणे.
password | वापरकर्ता संकेतशब्द.

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
