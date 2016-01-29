# Actualizando el proyecto

Drupal 8 está en constante desarrollo, para mantenerse en sicronía con los últimos cambios. La forma más rápida y recomendada de actualizar Drupal Console es usando el comando de auto-actualización.

## Tiene a su disposición distintos métodos de actualización:

### Instalando globalmente (y renombrando a "drupal"):
```
$ drupal self-update
```

### Instalando globalmente (usando composer):
```
$ composer global update drupal/console:@stable
```

### Instalando localmente (ejecutándolo desde el directorio donde se descargó console.phar):
```
$ php console.phar self-update
```

