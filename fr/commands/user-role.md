# user:role
Ajoute/retire un rôle à un utilisateur donné

**Usage:**
```
drupal user:role [arguments]
ur
```

## Available arguments
Argument | Details
---------|-------------
operation | Ajouter ou retirer
user | L'utilisateur concerné (un seul)
role | Rôles à ajouter ou à retirer. Merci de fournir le nom machine (un seul)

## Examples
* Add administrator role to the user admin specifying the username and the role
```
drupal user:role  add admin administrator
```
* Remove administrator role from the user admin specifying the username and the role
```
drupal user:role  remove admin administrator
```
