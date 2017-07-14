# config:diff
Az aktív konfigurációt egy könyvtárral összehasonlítva az eltérő konfigurációs elemek.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | Módosítások megtekintése fordítva (vagyis egy könyvtár összehasonlítása az aktív konfigurációval).

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | A könyvtár, amivel az összehasonlítást végezni kell. Ha nincs megadva, akkor a program a Drupal konfigurációs könyvtárakból választ.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
