# user:delete
ऐप्लकैशनचे वापरकर्ते हटवा.

**वापर:**
```
drupal user:delete [options]
ud
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--user | User name/id to be deleted
--roles | वापरकर्त्यांच्या संबंधित भूमिका हटविल्या जातील.

## उदाहरणे
* वापरकर्ताआयडीआणि वापरकर्ता भूमिका निर्दिष्ट करणारा हटवा.
```
drupal user:delete  \
  --user-id="2"
  --roles='authenticated'
```
* वापरकर्त्यास त्याचा आयडी निर्दिष्ट करून हटवा.
```
drupal user:delete  \
  --user-id="3"
```
* Delete users with the role "authenticated"
```
drupal user:delete  \
  --role="authenticated"
```
