# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Muestra información básica sobre el proyecto Drupal Console
[chain](chain.md) | Ejecución de comandos en secuencia
[check](check.md) | Comprobador de requisitos del sistema
[exec](exec.md) | Ejecutar un comando externo.
[help](help.md) | Muestra ayuda para un comando dado
[init](init.md) | Copia los archivos de configuración al directorio home del usuario.
[list](list.md) | Enlista comandos
[shell](shell.md) | Abre una shell que provee un REPL (Read–Eval–Print-Loop) interactiv0.
[server](server.md) | Lanza el servidor web PHP interno
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruye y limpia todas las cachés del sitio.
**config**  |
[config:delete](config-delete.md) | Eliminar configuración
[config:diff](config-diff.md) | Muestra los items de configuración que son diferentes en la configuración activa comparada con un directorio.
[config:edit](config-edit.md) | Editar la configuración seleccionada.
[config:export](config-export.md) | Exporta la configuración actual de la aplicación.
[config:export:content:type](config-export-content-type.md) | Exporta un tipo de contenido específico y sus campos.
[config:export:single](config-export-single.md) | Exporta configuración como fichero yml.
[config:export:view](config-export-view.md) | Exporta una vista en formato YAML dentro de un modulo para reutilizar en otro sitio web.
[config:import](config-import.md) | Importa la configuración del estado actual de la aplicación.
[config:import:single](config-import-single.md) | Importar la configuración seleccionada.
[config:override](config-override.md) | Sobreescribir valor de la configuración activa.
[config:validate](config-validate.md) | Validar una configuración de Drupal según su schema
**create**  |
[create:comments](create-comments.md) | Crear comentarios de prueba para tu aplicación en Drupal 8.
[create:nodes](create-nodes.md) | Crea nodos de relleno para su Drupal 8.
[create:terms](create-terms.md) | Crea términos de relleno para tu Drupal 8.
[create:users](create-users.md) | Crea usuarios de prueba para tu Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crea vocabularios de prueba para tu Drupal 8.
**cron**  |
[cron:execute](cron-execute.md) | Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones
[cron:release](cron-release.md) | Desbloquea al cron para volver a ejecutarlo
**database**  |
[database:add](database-add.md) | Añade una base de datos al settings.php
[database:client](database-client.md) | Lanzar un cliente de base de datos si está disponible
[database:connect](database-connect.md) | Lanzar un cliente de base de datos si está disponible
[database:drop](database-drop.md) | Muestra todas las tablas de una base de datos datos.
[database:dump](database-dump.md) | Volcado de la estructura y contenidos de las bases de datos y tablas MySQL
[database:log:clear](database-log-clear.md) | Eliminar eventos de la tabla DBLog, filtros disponibles
[database:log:poll](database-log-poll.md) | Observar el watchdog e imprimir nuevas entradas en el log cada x segundos
[database:query](database-query.md) | Ejecuta una sentencia SQL directamente como argumento
[database:restore](database-restore.md) | Restaurar la estructura y los contenidos de bases de datos y tablas MySQL
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Muestra los breakpoints disponibles en la aplicación
[debug:cache:context](debug-cache-context.md) | Muestra el contexto de caché actual para la aplicación.
[debug:chain](debug-chain.md) | Lista las secuencias de comandos disponibles.
[debug:config](debug-config.md) | Muestra la configuración actual.
[debug:config:settings](debug-config-settings.md) | Muestra el par clave:valor actual en el archivo de configuración.
[debug:config:validate](debug-config-validate.md) | Función helper para validar una implementación de schema antes de que sea instalado un módulo. Especifique las rutas de archivos de la configuración y el schema como argumentos y se lanzará la validación contra ellos, haciendo el schema más fácil de debugear ahorrando tiempo haciendo instalaciones
[debug:container](debug-container.md) | Muestra los servicios actuales de la aplicación.
[debug:cron](debug-cron.md) | Listado de módulos que implementan una llamada al cron
[debug:database:log](debug-database-log.md) | Desplegar eventos registrados al momento para la aplicación
[debug:database:table](debug-database-table.md) | Muestra todas las tablas en una base de datos.
[debug:entity](debug-entity.md) | Debugea entidades disponibles en el sistema
[debug:event](debug-event.md) | Mostrar los eventos actuales 
[debug:features](debug-features.md) | Ofrece un listado de las features registradas.
[debug:image:styles](debug-image-styles.md) | Lista los estilos de imágenes del sitio
[debug:libraries](debug-libraries.md) | Muestra las librerías disponibles en la aplicación
[debug:migrate](debug-migrate.md) | Muestra la migración actual disponible para la aplicación
[debug:module](debug-module.md) | Muestra los módulos actualmente disponibles para la aplicación
[debug:multisite](debug-multisite.md) | Lista todos los sitios múltiples disponibles en el sistema
[debug:permission](debug-permission.md) | Muestra todos los permisos y además lista todos los permisos de un especifico rol de usuario.
[debug:plugin](debug-plugin.md) | Mostrar todos los tipos de plugin, instancias de plugin de un tipo específico, o la definición para un plugin específico.
[debug:queue](debug-queue.md) | Muestra las colas de su aplicación
[debug:rest](debug-rest.md) | Muestra el actual recurso rest para la aplicación
[debug:router](debug-router.md) | Muestra las rutas actuales de la aplicación o la información detallada de una ruta en particular
[debug:settings](debug-settings.md) | Ofrece un listado de la configuración de usuario de Drupal Console.
[debug:site](debug-site.md) | Enlista todos los sitios, locales y remotos, conocidos.
[debug:state](debug-state.md) | Muestra las claves de Estado actual.
[debug:test](debug-test.md) | Lista los tests unitarios disponibles para la aplicación.
[debug:theme](debug-theme.md) | Despliega los temas actuales para la aplicación
[debug:update](debug-update.md) | Muestra las actualizaciones actualmente disponibles para la aplicación
[debug:user](debug-user.md) | Muestra los usuarios actuales del sitio
[debug:views](debug-views.md) | Muestra los recursos actuales de vistas para la aplicación
[debug:views:plugins](debug-views-plugins.md) | Mostrar los plugins de views en la aplicación
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**develop**  |
[develop:contribute](develop-contribute.md) | 
[develop:example](develop-example.md) | 
[develop:example:container:aware](develop-example-container-aware.md) | 
[develop:gitbook](develop-gitbook.md) | Update gitbook
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Elimina una entidad específica
**extend**  |
[extend:example:one](extend-example-one.md) | Drupal Console extend example
[extend:example:two](extend-example-two.md) | Drupal Console extend example
**features**  |
[features:import](features-import.md) | Importar módulo de configuración.
**field**  |
[field:info](field-info.md) | Muestra información sobre los campos.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveedor de Autenticación
[generate:breakpoint](generate-breakpoint.md) | Genera un breakpoint
[generate:cache:context](generate-cache-context.md) | Generata un contexto de caché
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
[generate:form](generate-form.md) | Genera un nuevo "%s"
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
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Genera un plugin de proceso para migración
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Genera un plugin de migración de fuentes
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
[image:styles:flush](image-styles-flush.md) | Ejecutar la función limpieza por cada uno o por todos los estilos de imágenes
**locale**  |
[locale:language:add](locale-language-add.md) | Añadir un idioma que sea soportado en el sitio
[locale:language:delete](locale-language-delete.md) | Eliminar un idioma soportado en el sitio
[locale:translation:status](locale-translation-status.md) | Lista de traducciones disponibles actualizadas
**migrate**  |
[migrate:execute](migrate-execute.md) | Ejecuta una migración que esté disponible para la aplicación
[migrate:rollback](migrate-rollback.md) | Hacer Rollback de una o varias migraciones
[migrate:setup](migrate-setup.md) | Cargar y crear las migraciones pertinentes para una base de datos heredada
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Descarga un módulo o varios en la aplicación
[module:install](module-install.md) | Instala un módulo o varios en la aplicación
[module:path](module-path.md) | Indicar la ruta relativa a un módulo (o su ruta absoluta)
[module:uninstall](module-uninstall.md) | Desinstala un módulo o varios en la aplicación
[module:update](module-update.md) | Actualizar el core, un módulo o varios en la aplicación
**multisite**  |
[multisite:new](multisite-new.md) | Prepara los archivos para una nueva instalación multisitio.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Reconstruir los permisos de acceso a nodos. La reconstrucción eliminará todos los privilegios al contenudo y los reemplazará con permisos basado en los módulos y configuración actual,
**queue**  |
[queue:run](queue-run.md) | Procesa la cola seleccionada.
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | Deshabilita un recurso rest en la aplicación
[rest:enable](rest-enable.md) | Habilita un recurso rest para la aplicación
**router**  |
[router:rebuild](router-rebuild.md) | Reconstruye las rutas de la aplicación
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Cambia un valor de configuración específico en el archivo de configuración de DrupalConsole
**site**  |
[site:import:local](site-import-local.md) | Importar o configurar un proyecto Drupal existente en local
[site:install](site-install.md) | Instala un proyecto Drupal
[site:maintenance](site-maintenance.md) | Poner el sitio en modo mantenimiento
[site:mode](site-mode.md) | Cambiar la configuración de rendimiento del sistema
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | Muestra las estadísticas actuales del sitio web.
[site:status](site-status.md) | Ver el estatus de la instalación actual de Drupal
**state**  |
[state:delete](state-delete.md) | Eliminar Estado
[state:override](state-override.md) | Sobreescribir una clave de Estado.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Elimina términos de taxonomía de un vocabulario, este comando toma el VID como argumento o, si no se pasa ninguno, serán eliminados todos los términos de todos los vocabularios
**test**  |
[test:run](test-run.md) | Ejecuta un test unitario de los disponibles en la aplicación
**theme**  |
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
[update:entities](update-entities.md) | Aplicar actualizaciones a entidades
[update:execute](update-execute.md) | Ejecuta una función específica de Actualizar N dentro de un módulo, o ejecutarlos todos
**user**  |
[user:create](user-create.md) | Crea usuarios para la aplicación
[user:delete](user-delete.md) | Eliminar usuarios del sitio
[user:login:clear:attempts](user-login-clear-attempts.md) | Limpia intentos de inicio de sesión fallidos para una cuenta.
[user:login:url](user-login-url.md) | Crea una url de login de usuario de uso único.
[user:password:hash](user-password-hash.md) | Crea un hash a partir de una contraseña en texto plano.
[user:password:reset](user-password-reset.md) | Restablece la contraseña de un usuario específico.
[user:role](user-role.md) | Añadir/eliminar un rol de un usuario dado
**views**  |
[views:disable](views-disable.md) | Deshabilita una vista
[views:enable](views-enable.md) | Habilita una vista

## Available options
Option | Details
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
--debug | application.options.debug
--learning | Generar código con explicaciones.
--generate-chain | Imprimir opciones y argumentos como YAML para ser usado el comando chain
--generate-inline | Imprimir opciones y argumentos de ejecución como llamada inline para ser usados en el futuro
--generate-doc | Muestra las opciones del comando y sus argumentos como markdown
--target | Nombre del sitio con el que desea interactuar (sitio remoto o local)
--uri | URI del sitio en Drupal que se usará (para ambientes en multi-site o cuando esta usando un puerto alternativo)
--yes | Saltar confirmación y ejecutar directamente

## Available arguments
Argument | Details
---------|-------------
command | El comando a ejecutar
