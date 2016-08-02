# generate:controller
Generate & Register a controller

**Használat:**
```
$ drupal generate:controller [options]
$ gcn  
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--module | The Module name.
--class | Controller Class name
--routes | The routes, must be an array containing [title, method, path]
--services | Load services from the container.
--test | Generate a test class
