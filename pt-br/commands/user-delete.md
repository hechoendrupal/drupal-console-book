# user:delete
Remover usuários da aplicação

**Utilização:**
```
drupal user:delete [options]
ud
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--user | User name/id to be deleted
--roles | Papéis associados ao usuários que serão deletados

## Exemplos
* Delete user specifying the id and the user role
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* Delete user specifying its id
```
drupal user:delete  \
  --user-id="3"
```
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
