# config:diff
Az aktív konfigurációt egy könyvtárral összehasonlítva az eltérő konfigurációs elemek.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal config:diff [arguments] [options]
$ cdi  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--reverse | Módosítások megtekintése fordítva (vagyis egy könyvtár összehasonlítása az aktív konfigurációval).

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
directory | A könyvtár, amivel az összehasonlítást végezni kell. Ha nincs megadva, akkor a program a Drupal konfigurációs könyvtárakból választ.

## commands.generate.doc.gitbook.messages.examples
* Provide a config directory
```
$ drupal config:diff ../config/path
```
