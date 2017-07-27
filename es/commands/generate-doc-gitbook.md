# generate:doc:gitbook
Generar documentaciones para Comandos

**Uso:**
```
drupal generate:doc:gitbook [arguments] [options]
gdg
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--path | La ruta donde exportar la documentación
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | Nombre del ambiente.
--root | Define la raíz de Drupal que se utilizará en la ejecución de los comandos
--debug | application.options.debug
--learning | Generar código con explicaciones.
--generate-chain | Imprimir opciones y argumentos como YAML para ser usado el comando chain
--generate-inline | Imprimir opciones y argumentos de ejecución como llamada inline para ser usados en el futuro
--generate-doc | Muestra las opciones del comando y sus argumentos como markdown
--target | Nombre del sitio con el que desea interactuar (sitio remoto o local)
--uri | URI del sitio en Drupal que se usará (para ambientes en multi-site o cuando esta usando un puerto alternativo)
--yes | Saltar confirmación y ejecutar directamente

## Argumentos disponibles
Argumento | Detalles
---------|-------------
command | The command to execute
