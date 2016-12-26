# config:export
Exporta la configuración actual de la aplicación.

**Uso:**
```
$ drupal config:export [options]
$ ce  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--directory | Define el directorio de exportación para guardar la configuración.
--tar | Indique esta opción para exportar la configuración a un archivo.
--remove-uuid | Si se utiliza, la configuración será exportada sin clave uuid.
--remove-config-hash | Si se utiliza, la configuración será exportada sin la clave hash por defecto del sitio.
