# database:drop
एक दिए गए डेटाबेस में सभी टेबल्स ड्राप।

**application.gitbook.messages.usage:**
```
drupal database:drop [arguments]
dbd
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
database | Settings.php से डाटाबेस कुंज

## application.gitbook.messages.examples
* Drop the tables on the database specified on the argument
```
drupal database:drop \
  <database>
```
