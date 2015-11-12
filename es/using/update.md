# Actualizando el proyecto

Drupal 8 está en un fuerte desarrollo, para mantenerse en sicronía con los últimos cambios. LA forma más rápida y recomendada para actualizar Drupal Console es usando el comando de auto actualización.

## Dependiendo del método de actualización:

### Instalando globalmente (y renombrando a "drupal"):
```
$ drupal self-update
```

### Instalando globalmente (usando composer):
```
$ composer global update drupal/console:@stable
```

### Instalando localmente (ejecutandolo desde el directorio donde se descargó console.phar):
```
$ php console.phar self-update
```

