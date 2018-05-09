# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Detalls
------------ | -------------
**misc**  |
[about](about.md) | Mostrar l'informació bàsica sobre el projecte Drupal Console
[chain](chain.md) | Execució de comandaments en secuència
[check](check.md) | System requirement checker
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Execute an external command.
[help](help.md) | Mostrar l'ajuda per un comandament
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Llistar tots els comandaments disponibles
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Executar el servidor PHP integrat
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruir i esborrar la memòria cau del lloc web.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Sortida dels elements de configuració diferents a la configuració activa comparada amb un directori.
[config:edit](config-edit.md) | Editar la configuració seleccionada
[config:export](config-export.md) | Exportar la configuració actual de l'aplicació
[config:export:content:type](config-export-content-type.md) | Exportar un tipus de contingut i els seus camps.
[config:export:single](config-export-single.md) | Exportar la configuració com a fitxer YML
[config:export:view](config-export-view.md) | Exportar una vista amb el format YAML en un mòdul per reutilitzar-lo en un altre lloc web.
[config:import](config-import.md) | Importar la configuració a l'aplicació actual.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Sobreescriure el valor de la configuració activa.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Crear nodes 'dummy' per l'aplicació Drupal 8.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Crear termes 'dummy' per l'aplicació Drupal 8.
[create:users](create-users.md) | Crear usuaris 'dummy' per l'aplicació Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crear vocabulari 'dummy' per l'aplicació Drupal 8.
**cron**  |
[cron:execute](cron-execute.md) | Executar l'implementació de cron per mòdul o executar-los tots
[cron:release](cron-release.md) | Desbloquejar el cron del sistema per tornar-lo a executar
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Executar un client de base de dades
[database:connect](database-connect.md) | Llançar un client de base de dades
[database:drop](database-drop.md) | Esborrar les taules d'una base de dades.
[database:dump](database-dump.md) | Còpia de seguretat d'estructura, continguts i taules de la base de dades MySQL
[database:log:clear](database-log-clear.md) | Eliminar esdeveniments de la taula DBLog, filtre disponible
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restaurar l'estructura, continguts i taules de la base de dades MySQL
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | Mostrar la configuració actual
[debug:config:settings](debug-config-settings.md) | Mostra l'actual clau:valor del fitxer de configuració.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Mostrar els serveis actuals de l'aplicació.
[debug:cron](debug-cron.md) | Llistar els mòduls que implementen una crida al cron
[debug:database:log](debug-database-log.md) | Mostrar el registre d'esdeveniments actual de l'aplicació
[debug:database:table](debug-database-table.md) | Mostrar les taules d'una base de dades.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Mostrar les migracions disponibles per l'aplicació
[debug:module](debug-module.md) | Mostrar els mòduls disponibles per l'aplicació
[debug:multisite](debug-multisite.md) | Mostrar tots els multisites disponibles del sistema
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Mostrar l'actual recurs Rest de l'aplicació
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Mostrar les rutes actuals per l'aplicació
[debug:settings](debug-settings.md) | Mostrar la clau actual: valor del fitxer de configuració.
[debug:site](debug-site.md) | Llistar tots els llocs locals i remots coneguts.
[debug:state](debug-state.md) | Mostrar l'estat actual de les claus.
[debug:test](debug-test.md) | Llistar els Test Units disponibles per l'aplicació.
[debug:theme](debug-theme.md) | Mostrar els temes actuals per l'aplicació
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | Mostrar les actualitzacions disponibles per l'aplicació
[debug:user](debug-user.md) | Mostrar els usuaris actuals de l'aplicació
[debug:views](debug-views.md) | Mostrar els recursos de vistes actuals de l'aplicació
[debug:views:plugins](debug-views-plugins.md) | Display current views plugins for the application
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveïdor d'Autenticació
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Generar comandaments per la consola
[generate:controller](generate-controller.md) | Generar i registrar un controlador
[generate:entity:bundle](generate-entity-bundle.md) | Generar un nou tipus de contingut (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generar una nova entitat de continguts
[generate:entity:content](generate-entity-content.md) | Generar una entitat de contingut
[generate:event:subscriber](generate-event-subscriber.md) | Generar un subscriptor d'esdeveniments
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generar una implementació de hook_form_alter() o hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Generar un mòdul
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
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
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generar un connector de recursos Rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generar un connector d'acció de regla
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generar un tipus de connector amb descobriment d'anotació
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generar un tipus de connector amb descobriment de YAML
[generate:plugin:views:field](generate-plugin-views-field.md) | Generar un connector de camp de vista predeterminat.
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | Generar un perfil.
[generate:routesubscriber](generate-routesubscriber.md) | Generar una ruta de subcriptor (RouteSubscriber)
[generate:service](generate-service.md) | Generar un servei
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Generar un tema.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Afegir un idioma per el teu lloc web
[locale:language:delete](locale-language-delete.md) | Esborrar un idioma del teu lloc web
[locale:translation:status](locale-translation-status.md) | LListar les actualitzacions de les traduccions disponibles
**migrate**  |
[migrate:execute](migrate-execute.md) | Executar les migracions disponibles per l'aplicació
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Carregar i crear migracions proveïdes per una base de dades heretada
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Descarregar mòduls a la aplicació
[module:install](module-install.md) | Instal·lar mòdul en l'aplicació
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Desintal·lar mòdul(s) en l'aplicació
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:disable](rest-disable.md) | Deshabilitar el recurs Rest per l'aplicació
[rest:enable](rest-enable.md) | Habilitar un recurs Rest per l'aplicació
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Reconstruir rutes per l'aplicació
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Canviar un valor especific al fitxer de configuració de Drupal Console
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Instal·lar un projecte Drupal
[site:maintenance](site-maintenance.md) | Canviar al mode manteniment
[site:mode](site-mode.md) | Canviar la configuració de rendiment del sistema
[site:statistics](site-statistics.md) | Mostrar les estadístiques del lloc web.
[site:status](site-status.md) | Veure l'estat actual de l'instal·lació de Drupal
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Anul·lar l'estat de la clau.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Executa els Test Units disponibles per l'aplicació
**theme**  |
[theme:download](theme-download.md) | Descarregar tema per l'aplicació
[theme:install](theme-install.md) | Instal·lar temes per l'aplicació
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Desinstal·lar els temes de l'aplicació
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Executar una funció Update N en un mòdul, o executar-les totes
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Eliminar usuaris de l'aplicació
[user:login:clear:attempts](user-login-clear-attempts.md) | Esborrar els intents de connexió d'un compte.
[user:login:url](user-login-url.md) | Generar la 'one-time login url' del usuari.
[user:password:hash](user-password-hash.md) | Generar un 'hash' a partir d'una contrasenya de text sense format.
[user:password:reset](user-password-reset.md) | Reinicialitzar una contrasenya per un usuari determinat.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Deshabilitar les vistes
[views:enable](views-enable.md) | Habilitar les vistes

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
--debug | Switches on debug mode
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
