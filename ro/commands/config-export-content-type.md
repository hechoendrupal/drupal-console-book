# config:export:content:type
Exportă un anumit tip de conținut și câmpurile aferente.

**application.gitbook.messages.usage:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Numele Modulului.
--optional-config | Exportă tipul de conținut ca un fișier opțional de configurare YAML în modulul tău

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
content-type | Content Type to be exported

## application.gitbook.messages.examples
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
