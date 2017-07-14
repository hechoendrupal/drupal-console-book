# server
Runs PHP built-in web server

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal server [arguments]
```

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
address | The address:port values

## commands.generate.doc.gitbook.messages.examples
* Run using default address argument value 127.0.0.1:8088
```
drupal server
```
* Passing address argument to use a different port number
```
drupal server 127.0.0.1:8089
```
* Running default address argument values, using --root option to define the Drupal root
```
drupal --root=/var/www/drupal8.dev server
```
