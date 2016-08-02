# Comandaments disponibles de Drupal

**Nota:** Els comandaments de Drupal Console *han* de ser executats a la rel de la'instal·lació de Drupal 8.

Comandaments de Drupal Console | Detalls
------------ | -------------
[about](about.md) | Mostrar l'informació bàsica sobre el projecte Drupal Console
[chain](chain.md) | Execució de comandaments en secuència
[check](check.md) | System requirement checker
[help](help.md) | Mostrar l'ajuda per un comandament
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Llistar tots els comandaments disponibles
[self-update](self-update.md) | Actualitzar el projecte a l'última versió.
[server](server.md) | Executar el servidor PHP integrat
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | Displays breakpoints available in application
**cache**  |
[cache:context:debug](cache-context-debug.md) | Displays current cache context for the application.
[cache:rebuild](cache-rebuild.md) | Reconstruir i esborrar la memòria cau del lloc web.
**chain**  |
[chain:debug](chain-debug.md) | List available chain files.
**config**  |
[config:debug](config-debug.md) | Mostrar la configuració actual
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Sortida dels elements de configuració diferents a la configuració activa comparada amb un directori.
[config:edit](config-edit.md) | Editar la configuració seleccionada
[config:export](config-export.md) | Exportar la configuració actual de l'aplicació
[config:export:content:type](config-export-content-type.md) | Exportar un tipus de contingut i els seus camps.
[config:export:view](config-export-view.md) | Exportar una vista amb el format YAML en un mòdul per reutilitzar-lo en un altre lloc web.
[config:import](config-import.md) | Importar la configuració a l'aplicació actual.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Sobreescriure el valor de la configuració activa.
[config:settings:debug](config-settings-debug.md) | Mostra l'actual clau:valor del fitxer de configuració.
**container**  |
[container:debug](container-debug.md) | Mostrar els serveis actuals de l'aplicació.
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Crear nodes 'dummy' per l'aplicació Drupal 8.
[create:terms](create-terms.md) | Crear termes 'dummy' per l'aplicació Drupal 8.
[create:users](create-users.md) | Crear usuaris 'dummy' per l'aplicació Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crear vocabulari 'dummy' per l'aplicació Drupal 8.
**cron**  |
[cron:debug](cron-debug.md) | Llistar els mòduls que implementen una crida al cron
[cron:execute](cron-execute.md) | Executar l'implementació de cron per mòdul o executar-los tots
[cron:release](cron-release.md) | Desbloquejar el cron del sistema per tornar-lo a executar
**database**  |
[database:client](database-client.md) | Executar un client de base de dades
[database:connect](database-connect.md) | Llançar un client de base de dades
[database:drop](database-drop.md) | Esborrar les taules d'una base de dades.
[database:dump](database-dump.md) | Còpia de seguretat d'estructura, continguts i taules de la base de dades MySQL
[database:log:clear](database-log-clear.md) | Eliminar esdeveniments de la taula DBLog, filtre disponible
[database:log:debug](database-log-debug.md) | Mostrar el registre d'esdeveniments actual de l'aplicació
[database:restore](database-restore.md) | Restaurar l'estructura, continguts i taules de la base de dades MySQL
[database:table:debug](database-table-debug.md) | Mostrar les taules d'una base de dades.
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | Display current events 
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveïdor d'Autenticació
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:command](generate-command.md) | Generar comandaments per la consola
[generate:controller](generate-controller.md) | Generar i registrar un controlador
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | Generar la documentació per els comandaments
[generate:doc:data](generate-doc-data.md) | Generate documentations for Commands.
[generate:doc:gitbook](generate-doc-gitbook.md) | Generar la documentació per els comandaments
[generate:entity:bundle](generate-entity-bundle.md) | Generar un nou tipus de contingut (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generar una nova entitat de continguts
[generate:entity:content](generate-entity-content.md) | Generar una entitat de contingut
[generate:event:subscriber](generate-event-subscriber.md) | Generar un subscriptor d'esdeveniments
[generate:form](generate-form.md) | Generar un nou "FormBase"
[generate:form:alter](generate-form-alter.md) | Generar una implementació de hook_form_alter() o hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generar un nou "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Generar un mòdul
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generar els permisos del mòdul
[generate:plugin:block](generate-plugin-block.md) | Generar un connector de bloc
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Generar una condició per a un connector
[generate:plugin:field](generate-plugin-field.md) | Generar connectors de tipus de camp, giny i formatador de connectors
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generar un connector formatador de camp.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generar connector de tipus de camp.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generar connector de giny de camp.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generar un connector d'efecte d'imatge.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generar un connector formatador de camp.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generar un connector de recursos Rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generar un connector d'acció de regla
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generar un tipus de connector amb descobriment d'anotació
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generar un tipus de connector amb descobriment de YAML
[generate:plugin:views:field](generate-plugin-views-field.md) | Generar un connector de camp de vista predeterminat.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Generar un perfil.
[generate:routesubscriber](generate-routesubscriber.md) | Generar una ruta de subcriptor (RouteSubscriber)
[generate:service](generate-service.md) | Generar un servei
[generate:theme](generate-theme.md) | Generar un tema.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | Displays libraries available in application
**locale**  |
[locale:language:add](locale-language-add.md) | Afegir un idioma per el teu lloc web
[locale:language:delete](locale-language-delete.md) | Esborrar un idioma del teu lloc web
[locale:translation:status](locale-translation-status.md) | LListar les actualitzacions de les traduccions disponibles
**migrate**  |
[migrate:debug](migrate-debug.md) | Mostrar les migracions disponibles per l'aplicació
[migrate:execute](migrate-execute.md) | Executar les migracions disponibles per l'aplicació
**module**  |
[module:debug](module-debug.md) | Mostrar els mòduls disponibles per l'aplicació
[module:download](module-download.md) | Descarregar mòduls a la aplicació
[module:install](module-install.md) | Instal·lar mòdul en l'aplicació
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Desintal·lar mòdul(s) en l'aplicació
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | Mostrar tots els multisites disponibles del sistema
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**queue**  |
[queue:debug](queue-debug.md) | Display the queues of your application
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:debug](rest-debug.md) | Mostrar l'actual recurs Rest de l'aplicació
[rest:disable](rest-disable.md) | Deshabilitar el recurs Rest per l'aplicació
[rest:enable](rest-enable.md) | Habilitar un recurs Rest per l'aplicació
**router**  |
[router:debug](router-debug.md) | Mostrar les rutes actuals per l'aplicació
[router:rebuild](router-rebuild.md) | Reconstruir rutes per l'aplicació
**settings**  |
[settings:debug](settings-debug.md) | Mostrar la clau actual: valor del fitxer de configuració.
[settings:set](settings-set.md) | Canviar un valor especific al fitxer de configuració de Drupal Console
**site**  |
[site:debug](site-debug.md) | Llistar tots els llocs locals i remots coneguts.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Instal·lar un projecte Drupal
[site:maintenance](site-maintenance.md) | Canviar al mode manteniment
[site:mode](site-mode.md) | Canviar la configuració de rendiment del sistema
[site:new](site-new.md) | Crear un nou projecte Drupal
[site:statistics](site-statistics.md) | Mostrar les estadístiques del lloc web.
[site:status](site-status.md) | Veure l'estat actual de l'instal·lació de Drupal
**state**  |
[state:debug](state-debug.md) | Mostrar l'estat actual de les claus.
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Anul·lar l'estat de la clau.
**test**  |
[test:debug](test-debug.md) | Llistar els Test Units disponibles per l'aplicació.
[test:run](test-run.md) | Executa els Test Units disponibles per l'aplicació
**theme**  |
[theme:debug](theme-debug.md) | Mostrar els temes actuals per l'aplicació
[theme:download](theme-download.md) | Descarregar tema per l'aplicació
[theme:install](theme-install.md) | Instal·lar temes per l'aplicació
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Desinstal·lar els temes de l'aplicació
**translation**  |
[translation:cleanup](translation-cleanup.md) | Netejar el fitxer de traduccions
[translation:pending](translation-pending.md) | Determinar cadena de traduccions pendent en un idioma o en un fitxer especific d'un idioma
[translation:stats](translation-stats.md) | Generar estadístiques de traduccions
[translation:sync](translation-sync.md) | Sincronitzar fitxer de traduccions
**update**  |
[update:debug](update-debug.md) | Mostrar les actualitzacions disponibles per l'aplicació
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Executar una funció Update N en un mòdul, o executar-les totes
**user**  |
[user:debug](user-debug.md) | Mostrar els usuaris actuals de l'aplicació
[user:delete](user-delete.md) | Eliminar usuaris de l'aplicació
[user:login:clear:attempts](user-login-clear-attempts.md) | Esborrar els intents de connexió d'un compte.
[user:login:url](user-login-url.md) | Generar la 'one-time login url' del usuari.
[user:password:hash](user-password-hash.md) | Generar un 'hash' a partir d'una contrasenya de text sense format.
[user:password:reset](user-password-reset.md) | Reinicialitzar una contrasenya per un usuari determinat.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:debug](views-debug.md) | Mostrar els recursos de vistes actuals de l'aplicació
[views:disable](views-disable.md) | Deshabilitar les vistes
[views:enable](views-enable.md) | Habilitar les vistes
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | Comparar dos fitxers YAML.
[yaml:merge](yaml-merge.md) | Combinar un o més fitxers YAML en un nou fitxer YAML. Es conserven els últims valors.
[yaml:split](yaml-split.md) | Dividir un fitxer YAML utilitzant una indentació com a criteri de separació
[yaml:update:key](yaml-update-key.md) | Reemplaçar una clau YAML en un fitxer YAML.
[yaml:update:value](yaml-update-value.md) | Actualitzar un valor per una clau determinada d'un fitxer YAML.

## Opcions disponibles
Opció | Detalls
-------|-------------
--help | Mostrar aquest missatge d'ajuda
--quiet | No mostrar aquest missatge
--verbose | Augmentar el detall dels missatges: 1 per una sortida normal, 2 per una sortida més detallada i 3 per depurar
--version | <info>"%s"</info> versió <comment>"%s"</comment>
--ansi | Forçar sortida ANSI
--no-ansi | Deshabilitar sortida ANSI
--no-interaction | No fer cap pregunta de forma interactiva
--env | Nom de l'entorn
--root | Definir el camí arrel de Drupal on s'executaran els comandaments
--no-debug | Desactivar el mode de depuració.
--learning | Generar codi detallat.
--generate-chain | Imprimir les opcions d'execució i els arguments com una sortida YAML per ser utilitzats amb el comandament "chain".
--generate-inline | Imprimir les opcions d'execució i els arguments com inserits per ser utilitzats en un futur.
--generate-doc | Mostrar les opcions i arguments dels comandaments com a "markdown"
--target | El nom del lloc web amb el qual vols interactuar (locals o remot)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Ometre la confirmació

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
