# server
A PHP beépített webkiszolgálójának futtatása

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal server [arguments]
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
address | A cím:port értékek

## commands.generate.doc.gitbook.messages.examples
* Futtatás az alapértelmezett cím argumentumértékkel: 127.0.0.1:8088
```
$ drupal server
```
* Cím argumentum átadása másik portszám használatához
```
$ drupal server 127.0.0.1:8089
```
* Alapértelmezett cím argumentumértékek futtatása, --root paraméter használata a Drupal gyökér megadására
```
$ drupal --root=/var/www/drupal8.dev server
```
