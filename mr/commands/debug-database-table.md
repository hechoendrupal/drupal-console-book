# debug:database:table
दिलेल्या डेटाबेसमध्ये सर्व सारण्या दर्शवा.

**Usage:**
```
drupal debug:database:table [arguments] [options]
ddt
```

## Available options
Option | Details
-------|-------------
--database | Settings.php पासून डेटाबेस की.

## Available arguments
Argument | Details
---------|-------------
table | टेबल डीबग करण्यासाठी.

## Examples
* Show all tables on a database
```
drupal debug:database:table
```
* Show fields on the node table or another specified on the argument
```
drupal debug:database:table node
```
