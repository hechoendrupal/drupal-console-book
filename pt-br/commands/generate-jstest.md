# generate:jstest
Generate a JavaScript test.

**Utilização:**
```
drupal generate:jstest [options]
gjt
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | JavaScript test Class name

## Exemplos
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
