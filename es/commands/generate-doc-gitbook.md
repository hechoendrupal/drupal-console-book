# generate:doc:gitbook
El comando **generate:doc:gitbook** Generar documentaciones para Comandos

**Uso:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--path | La ruta donde exportar la documentación
--learning | Generar código con explicaciones.
--help | Muestra este mensaje de ayuda
--quiet | No mostrar ningún mensaje
--verbose | Aumentar el detalle de los mensajes: 1 para salida normal, 2 para una salida más explícita y 3 para debug
--version | Muestra la versión de esta aplicación
--ansi | Forzar salida ANSI
--no-ansi | Deshabilitar salida ANSI
--no-interaction | No hacer ninguna pregunta interactiva
--env | Nombre del ambiente.
--root | Define la raíz de Drupal que se utilizará en la ejecución de los comandos
--no-debug | Desactivar el modo de depuración.
--generate-chain | Imprimir opciones y argumentos como YAML para ser usado el comando chain
--generate-inline | Imprimir opciones y argumentos de ejecución como llamada inline para ser usados en el futuro
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI del sitio en Drupal que se usará (para ambientes en multi-site o cuando esta usando un puerto alternativo)
--yes | Skip confirmation and proceed

## Argumentos disponibles
Argumento | Detalles
---------|-------------
command | El comando a ejecutar
