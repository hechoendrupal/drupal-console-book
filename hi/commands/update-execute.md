# update:execute
मोड्यूल के किसी विशेष नवीनीकरण N फंक्शन को चलायें या सभी को चलायें।

**Usage:**
```
drupal update:execute [arguments]
upex
updb
```

## Available arguments
Argument | Details
---------|-------------
module | मोड्यूल का नाम।
update-n | commands.update.execute.options.update-n

## Examples
* Update all entities
```
drupal update:execute
```
* Execute updates for system module
```
drupal update:execute system
```
