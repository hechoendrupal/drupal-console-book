# user:role
Adds/removes a role for a given user

**Utilização:**
```
drupal user:role [arguments]
ur
```

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
operation | Add or remove
user | The affected user (only one)
role | Roles to add or remove. Please provide the machine name (only one)

## Exemplos
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
