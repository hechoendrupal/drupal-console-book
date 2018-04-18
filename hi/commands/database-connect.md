# database:connect
लॉन्च एक DB क्लाइंट अगर यह उपलब्ध है

**Usage:**
```
drupal database:connect [arguments]
dbco
sqlc
```

## Available arguments
Argument | Details
---------|-------------
database | Settings.php से डाटाबेस कुंज

## Examples
* Connects to an specified database, or the default if not arguments passed
```
drupal database:connect \
  <database>
```
