# module:update
Actualizar el core, un módulo o varios en la aplicación

**Uso:**
```
$ drupal module:update [arguments] [options]
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--composer | Actualizar el módulo usando Composer
--simulate | Simular el proceso de actualización con Composer

## Argumentos disponibles
Argumento | Detalles
---------|-------------
module | El módulo o módulos que vayan a ser actualizados deberían estar separados por un espacio. Déjelo vacío para actualizar el core y todos los módulos gestionados por Composer.
