# Comandos Drupal Console disponibles

**Nota:** Comandos de Drupal Console que *deben* ser ejecutados desde una instalación de Drupal 8.

Comando de Drupal Console | Detalles
------------ | -------------
[about](about.md) | Muestra información básica sobre el proyecto Drupal Console
[chain](chain.md) | Ejecución de comandos en secuencia
[check](check.md) | Comprobador de requisitos del sistema
[help](help.md) | Muestra ayuda para un comando dado
[init](init.md) | Copiar los archivos de configuración al directorio home del usuario.
[list](list.md) | Enlista comandos
[self-update](self-update.md) | Update project to the latest version.
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
[config:export:content:type](config-export-content-type.md) | Exporta un tipo de contenido determinado y todos sus campos.
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
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | Mostrar los eventos actuales 
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:data](generate-doc-data.md) | Generate documentations for Commands.
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Generate a module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:debug](image-styles-debug.md) | Lista los estilos de imágenes del sitio
[image:styles:flush](image-styles-flush.md) | Ejecutar la función limpieza por cada uno o por todos los estilos de imágenes
**libraries**  |
[libraries:debug](libraries-debug.md) | Muestra las librerías disponibles en la aplicación
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Muestra la migración actual disponible para la aplicación
[migrate:execute](migrate-execute.md) | Ejecuta una migración que esté disponible para la aplicación
**module**  |
[module:debug](module-debug.md) | Muestra los módulos actualmente disponibles para la aplicación
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
[queue:debug](queue-debug.md) | Display the queues of your application
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:debug](rest-debug.md) | Muestra el actual recurso rest para la aplicación
[rest:disable](rest-disable.md) | Deshabilita un recurso rest en la aplicación
[rest:enable](rest-enable.md) | Habilita un recurso rest para la aplicación
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
[site:new](site-new.md) | Crea un nuevo proyecto Drupal
[site:statistics](site-statistics.md) | Muestra las estadísticas actuales del sitio web.
[site:status](site-status.md) | Ver el estatus de la instalación actual de Drupal
**state**  |
[state:debug](state-debug.md) | Muestra las claves de Estado actual.
[state:delete](state-delete.md) | Eliminar Estado
[state:override](state-override.md) | Sobreescribir una clave de Estado.
**test**  |
[test:debug](test-debug.md) | Lista los tests unitarios disponibles para la aplicación.
[test:run](test-run.md) | Ejecuta un test unitario de los disponibles en la aplicación
**theme**  |
[theme:debug](theme-debug.md) | Despliega los temas actuales para la aplicación
[theme:download](theme-download.md) | Descarga un tema para la aplicación
[theme:install](theme-install.md) | Instalar tema o temas en la aplicación
[theme:path](theme-path.md) | Devuelve la ruta relativa al theme (o ruta absoluta)
[theme:uninstall](theme-uninstall.md) | Desinstalar tema o temas en la aplicación
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
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
