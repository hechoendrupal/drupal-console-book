# database:drop
एक दिए गए डेटाबेस में सभी टेबल्स ड्राप।

**Usage:**
```
drupal database:drop [arguments]
dbd
```

## Available arguments
Argument | Details
---------|-------------
database | Settings.php से डाटाबेस कुंज

## Examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
