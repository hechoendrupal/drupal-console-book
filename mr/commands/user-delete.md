# user:delete
ऐप्लकैशनचे वापरकर्ते हटवा.

**Usage:**
```
drupal user:delete [options]
ud
```

## Available options
Option | Details
-------|-------------
--user-id | वापरकर्ता आयडी हटवण्यात आला आहे.
--roles | वापरकर्त्यांच्या संबंधित भूमिका हटविल्या जातील.

## Examples
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
