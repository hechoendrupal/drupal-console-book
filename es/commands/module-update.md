# module:update
Actualizar el core, un módulo o varios en la aplicación

**application.gitbook.messages.usage:**
```
drupal module:update [arguments] [options]
moup
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--composer | Actualizar el módulo usando Composer
--simulate | Simular el proceso de actualización con Composer

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
module | El módulo o módulos que vayan a ser actualizados deberían estar separados por un espacio. Déjelo vacío para actualizar el core y todos los módulos gestionados por Composer.
