# Comandos Drupal Console disponibles

**Nota:** Comandos de Drupal Console que *deben* ser ejecutados desde una instalación de Drupal 8.

Comando de Drupal Console | Detalles
------------ | -------------
**misc**  |
[about](about.md) | Muestra información básica sobre el proyecto Drupal Console
[chain](chain.md) | Ejecución de comandos en secuencia
[check](check.md) | Comprobador de requisitos del sistema
[exec](exec.md) | Ejecutar un comando externo.
[help](help.md) | Muestra ayuda para un comando dado
[init](init.md) | Copia los archivos de configuración al directorio home del usuario.
[list](list.md) | Enlista comandos
[server](server.md) | Lanza el servidor web PHP interno
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | Muestra los breakpoints disponibles en la aplicación
**cache**  |
[cache:context:debug](cache-context-debug.md) | Muestra el contexto de caché actual para la aplicación.
[cache:rebuild](cache-rebuild.md) | Reconstruye y limpia todas las cachés del sitio.
**chain**  |
[chain:debug](chain-debug.md) | Lista las secuencias de comandos disponibles.
**config**  |
[config:debug](config-debug.md) | Muestra la configuración actual.
[config:delete](config-delete.md) | Eliminar configuración
[config:diff](config-diff.md) | Muestra los items de configuración que son diferentes en la configuración activa comparada con un directorio.
[config:edit](config-edit.md) | Editar la configuración seleccionada.
[config:export](config-export.md) | Exporta la configuración actual de la aplicación.
[config:export:content:type](config-export-content-type.md) | Exporta un tipo de contenido específico y sus campos.
[config:export:single](config-export-single.md) | Exportar configuración única como archivo YAML.
[config:export:view](config-export-view.md) | Exporta una vista en formato YAML dentro de un módulo para ser reutilizado en otro sitio.
[config:import](config-import.md) | Importa la configuración del estado actual de la aplicación.
[config:import:single](config-import-single.md) | Importar la configuración seleccionada.
[config:override](config-override.md) | Sobreescribir valor de la configuración activa.
[config:settings:debug](config-settings-debug.md) | Muestra el par clave:valor actual en el archivo de configuración.
**container**  |
[container:debug](container-debug.md) | Muestra los servicios actuales de la aplicación.
**create**  |
[create:comments](create-comments.md) | Crear comentarios de prueba para tu aplicación en Drupal 8.
[create:nodes](create-nodes.md) | Crea nodos de relleno para su Drupal 8.
[create:terms](create-terms.md) | Crea términos de relleno para tu Drupal 8.
[create:users](create-users.md) | Crea usuarios de prueba para tu Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crea vocabularios de prueba para tu Drupal 8.
**cron**  |
[cron:debug](cron-debug.md) | Listado de módulos que implementan una llamada al cron
[cron:execute](cron-execute.md) | Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones
[cron:release](cron-release.md) | Desbloquea al cron para volver a ejecutarlo
**database**  |
[database:client](database-client.md) | Lanzar un cliente de base de datos si está disponible
[database:connect](database-connect.md) | Lanzar un cliente de base de datos si está disponible
[database:drop](database-drop.md) | Muestra todas las tablas de una base de datos datos.
[database:dump](database-dump.md) | Volcado de la estructura y contenidos de las bases de datos y tablas MySQL
[database:log:clear](database-log-clear.md) | Eliminar eventos de la tabla DBLog, filtros disponibles
[database:log:debug](database-log-debug.md) | Desplegar eventos registrados al momento para la aplicación
[database:restore](database-restore.md) | Restaurar la estructura y los contenidos de bases de datos y tablas MySQL
[database:table:debug](database-table-debug.md) | Muestra todas las tablas en una base de datos.
**entity**  |
[entity:delete](entity-delete.md) | Elimina una entidad específica
**event**  |
[event:debug](event-debug.md) | Mostrar los eventos actuales 
**field**  |
[field:info](field-info.md) | Muestra información sobre los campos.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveedor de Autenticación
[generate:breakpoint](generate-breakpoint.md) | Genera un breakpoint
[generate:command](generate-command.md) | Genera un comando para la consola.
[generate:controller](generate-controller.md) | Generar y registrar un controlador
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Genera un cheatsheet imprimible de los comandos disponibles
[generate:doc:dash](generate-doc-dash.md) | Generar el paquete DrupalConsole.docset para Dash
[generate:doc:data](generate-doc-data.md) | Genera documentación para los comandos.
[generate:doc:gitbook](generate-doc-gitbook.md) | Generar documentaciones para Comandos
[generate:entity:bundle](generate-entity-bundle.md) | Genera un nuevo tipo de contenido (nodo / bundle de entidad)
[generate:entity:config](generate-entity-config.md) | Generar una nueva entidad de configuración
[generate:entity:content](generate-entity-content.md) | Generar una nueva entidad de contenido
[generate:event:subscriber](generate-event-subscriber.md) | Genera un suscriptor de eventos
[generate:form:alter](generate-form-alter.md) | Genera una implementación de hook_form_alter() o hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | Genera una implementación de hook_help()
[generate:module](generate-module.md) | Generar un módulo.
[generate:module:file](generate-module-file.md) | Generar un archivo .module
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | Genera un plugin de bloque
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Genera un plugin de botón para CKEditor.
[generate:plugin:condition](generate-plugin-condition.md) | Genera un plugin de condición.
[generate:plugin:field](generate-plugin-field.md) | Genera plugins de widget, formateador y tipo de campo.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Genera un plugin de formateador de campo.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Genera plugins de tipo de campo.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Genera un plugin de widget de campo.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Genera un plugin de efecto de imagen.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Genera plugins de formateador de imagen.
[generate:plugin:mail](generate-plugin-mail.md) | Genera un plugin de correo
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Genera un plugin de recurso rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Genera un plugin de acción de rules
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generar una implementación de un esqueleto de plugin para esos plugins de Drupal Console que no tienen un generador específico
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Genera un tipo de plugin con descubrimiento de anotaciones
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Genera un tipo de plugin con descubrimiento YAML
[generate:plugin:views:field](generate-plugin-views-field.md) | Genera un plugin de campo de vista personalizado.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Genera un perfil.
[generate:routesubscriber](generate-routesubscriber.md) | Generar un RouteSubscriber
[generate:service](generate-service.md) | Genera un servicio
[generate:theme](generate-theme.md) | Genera un tema.
[generate:twig:extension](generate-twig-extension.md) | Generar una extensión de Twig.
[generate:update](generate-update.md) | Generar una implementación de hook_update_N()
**image**  |
[image:styles:debug](image-styles-debug.md) | Lista los estilos de imágenes del sitio
[image:styles:flush](image-styles-flush.md) | Ejecutar la función limpieza por cada uno o por todos los estilos de imágenes
**libraries**  |
[libraries:debug](libraries-debug.md) | Muestra las librerías disponibles en la aplicación
**locale**  |
[locale:language:add](locale-language-add.md) | Añadir un idioma que sea soportado en el sitio
[locale:language:delete](locale-language-delete.md) | Eliminar un idioma soportado en el sitio
[locale:translation:status](locale-translation-status.md) | Lista de traducciones disponibles actualizadas
**module**  |
[module:debug](module-debug.md) | Muestra los módulos actualmente disponibles para la aplicación
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Descarga un módulo o varios en la aplicación
[module:install](module-install.md) | Instala un módulo o varios en la aplicación
[module:path](module-path.md) | Indicar la ruta relativa a un módulo (o su ruta absoluta)
[module:uninstall](module-uninstall.md) | Desinstala un módulo o varios en la aplicación
[module:update](module-update.md) | Actualizar el core, un módulo o varios en la aplicación
**multisite**  |
[multisite:debug](multisite-debug.md) | Lista todos los sitios múltiples disponibles en el sistema
[multisite:new](multisite-new.md) | Prepara los archivos para una nueva instalación multisitio.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Reconstruir los permisos de acceso a nodos. La reconstrucción eliminará todos los privilegios al contenudo y los reemplazará con permisos basado en los módulos y configuración actual,
**plugin**  |
[plugin:debug](plugin-debug.md) | Mostrar todos los tipos de plugin, instancias de plugin de un tipo específico, o la definición para un plugin específico.
**queue**  |
[queue:debug](queue-debug.md) | Muestra las colas de su aplicación
[queue:run](queue-run.md) | Procesa la cola seleccionada.
**router**  |
[router:debug](router-debug.md) | Muestra las rutas actuales de la aplicación
[router:rebuild](router-rebuild.md) | Reconstruye las rutas de la aplicación
**settings**  |
[settings:debug](settings-debug.md) | Ofrece un listado de la configuración de usuario de Drupal Console.
[settings:set](settings-set.md) | Cambia un valor de configuración específico en el archivo de configuración de DrupalConsole
**site**  |
[site:debug](site-debug.md) | Enlista todos los sitios, locales y remotos, conocidos.
[site:import:local](site-import-local.md) | Importar o configurar un proyecto Drupal existente en local
[site:install](site-install.md) | Instala un proyecto Drupal
[site:maintenance](site-maintenance.md) | Poner el sitio en modo mantenimiento
[site:mode](site-mode.md) | Cambiar la configuración de rendimiento del sistema
[site:statistics](site-statistics.md) | Muestra las estadísticas actuales del sitio web.
[site:status](site-status.md) | Ver el estatus de la instalación actual de Drupal
**state**  |
[state:debug](state-debug.md) | Muestra las claves de Estado actual.
[state:delete](state-delete.md) | Eliminar Estado
[state:override](state-override.md) | Sobreescribir una clave de Estado.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | commands.taxonomy.term.delete.description
**theme**  |
[theme:debug](theme-debug.md) | Despliega los temas actuales para la aplicación
[theme:download](theme-download.md) | Descarga un tema para la aplicación
[theme:install](theme-install.md) | Instalar tema o temas en la aplicación
[theme:path](theme-path.md) | Devuelve la ruta relativa al theme (o ruta absoluta)
[theme:uninstall](theme-uninstall.md) | Desinstalar tema o temas en la aplicación
**translation**  |
[translation:cleanup](translation-cleanup.md) | Ficheros de limpieza de traducción
[translation:pending](translation-pending.md) | Determina cadenas de traducción pendientes en un idioma o en un archivo específico de un idioma
[translation:stats](translation-stats.md) | Genera estadísticas de traducción
[translation:sync](translation-sync.md) | Sincronizar archivos de traducción
**update**  |
[update:debug](update-debug.md) | Muestra las actualizaciones actualmente disponibles para la aplicación
[update:entities](update-entities.md) | Aplicar actualizaciones a entidades
[update:execute](update-execute.md) | Ejecuta una función específica de Actualizar N dentro de un módulo, o ejecutarlos todos
**user**  |
[user:debug](user-debug.md) | Muestra los usuarios actuales del sitio
[user:delete](user-delete.md) | Eliminar usuarios del sitio
[user:login:clear:attempts](user-login-clear-attempts.md) | Limpia intentos de inicio de sesión fallidos para una cuenta.
[user:login:url](user-login-url.md) | Crea una url de login de usuario de uso único.
[user:password:hash](user-password-hash.md) | Crea un hash a partir de una contraseña en texto plano.
[user:password:reset](user-password-reset.md) | Restablece la contraseña de un usuario específico.
[user:role](user-role.md) | Añadir/eliminar un rol de un usuario dado
**views**  |
[views:debug](views-debug.md) | Muestra los recursos actuales de vistas para la aplicación
[views:disable](views-disable.md) | Deshabilita una vista
[views:enable](views-enable.md) | Habilita una vista
[views:plugins:debug](views-plugins-debug.md) | Mostrar los plugins de views en la aplicación
**yaml**  |
[yaml:diff](yaml-diff.md) | Compara dos archivos YAML para encontrar las diferencias entre ambos
[yaml:get:value](yaml-get-value.md) | Obtiene un valor para una clave específica en un archivo YAML.
[yaml:merge](yaml-merge.md) | Combinar uno o más archivos de YAML en un nuevo archivo YAML. Se conservarán los valores del archivo más a la izquierda del merge.
[yaml:split](yaml-split.md) | Divide un archivo YAML usando la indentación como criterio de separación
[yaml:update:key](yaml-update-key.md) | Reemplaza una clave en un archivo YAML.
[yaml:update:value](yaml-update-value.md) | Actualiza un valor de una clave específica en un archivo YAML.

## Opciones disponibles
Opción | Detalles
-------|-------------
--help | Muestra este mensaje de ayuda
--quiet | No mostrar ningún mensaje
--verbose | Aumenta la verbosidad de los mensajes: 1 para la salida normal, 2 para mayor verbosidad y 3 para depurar
--version | <info>"%s"</info> versión <comment>"%s"</comment>
--ansi | Forzar salida ANSI
--no-ansi | Deshabilitar salida ANSI
--no-interaction | No hacer ningura pregunta interactiva
--env | Nombre del ambiente.
--root | Define la raíz de Drupal que se utilizará en la ejecución de los comandos
--no-debug | Desactivar el modo de depuración.
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
command | El comando a ejecutar
