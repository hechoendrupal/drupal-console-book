# generate:controller
The **generate:controller** command Controller létrehozása és regisztrálása

**Usage:**
```
$ drupal generate:controller [options] 
$ gcn  
```

## Available options
Option | Details
-------|-------------
--module | A Modul neve.
--class | Controller Class neve
--routes | The routes, must be an array containing [title, method, path]
--services | Service betöltése a container-ből.
--test | Teszt osztály létrehozása
