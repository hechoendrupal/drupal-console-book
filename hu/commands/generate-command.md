# generate:command
Parancsok létrehozása a konzolhoz.

**application.gitbook.messages.usage:**
```
drupal generate:command [options]
gco
gcm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | A parancsot leíró osztály. (A 'Command' szóra kell végződnie).
--name | A parancs neve.
--container-aware | A parancs ismeri-e a drupal telepítési helyét a végrehajtáskor
--services | Szolgáltatások betöltése a tárolóból.
