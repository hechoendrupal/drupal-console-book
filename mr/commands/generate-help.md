# generate:help
hook_help() चे लागूकरण उत्पन्न करा.

**Usage:**
```
drupal generate:help [options]
gh
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--description | मॉड्यूल वर्णन.

## Examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
