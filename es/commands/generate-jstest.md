# generate:jstest
Genera un test Javascript.

**Uso:**
```
drupal generate:jstest [options]
gjt
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--module | Nombre del módulo.
--class | Nombre de la clase del test Javascript

## Ejemplos
* Generar un módulo especificando el nombre del módulo, el nombre máquina, la ruta, su descripción, el core de Drupal y el nombre del paquete. En este ejemplo el archivo de composer, el test unitario y la plantilla de Twig también se generan
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
