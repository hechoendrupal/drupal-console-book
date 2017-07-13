# generate:module
Modul létrehozása.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:module [options]
$ gm  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | A modul neve
--machine-name | A programok által használt név (csak kisbetűk és aláhúzás)
--module-path | A modul útvonala
--description | A modul leírása
--core | Drupal alaprendszer verziója
--package | Modulcsomag
--module-file | .module fájl hozzáadása
--features-bundle | Define module as feature using the given Features bundle name
--composer | composer.json fájl hozzáadása
--dependencies | Modulfüggőségek vesszővel elválasztva (pl. context, panels)
--test | Tesztosztály létrehozása
--twigtemplate | Generate theme template
