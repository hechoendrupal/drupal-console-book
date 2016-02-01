# Comandaments disponibles de Drupal

**Nota:** Els comandaments de Drupal Console *han* de ser executats a la rel de la'instal·lació de Drupal 8.

Commandaments de Drupal Console | Detalls
------------ | -------------
[about](about.md) | Mostra l'informació bàsica sobre el projecte Drupal Console
[chain](chain.md) | Execució de comandaments en secuència
[help](help.md) | Mostra l'ajuda per un comandament
[console:config:init](console-config-init.md) | commands.console.config.init.description
[list](list.md) | Llista tots els commandaments disponibles
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstrueix i esborra tota la memòria cau (cache) del lloc web.
**config**  |
[config:debug](config-debug.md) | Mostra la configuració actual
[config:edit](config-edit.md) | Editar la configuració seleccionada
[config:export](config-export.md) | Exporta la configuració actual de l'aplicació
[config:export:content:type](config-export-content-type.md) | Exporta un tipus de contingut i els seus camps.
[config:export:single](config-export-single.md) | Exportar configuració con a fitxer yml
[config:export:view](config-export-view.md) | Exporta un vista amb el format YAML en un mòdul per reutilitzar-ho en un altre lloc web.
[config:import](config-import.md) | Importa la configuració a l'aplicació actual.
[config:import:single](config-import-single.md) | Importar la configuració seleccionada.
[config:override](config-override.md) | Sobreescriure el valor de la configuració activa.
**console**  |
[console:config:init](console-config-init.md) | commands.console.config.init.description
[console:config:set:language](console-config-set-language.md) | commands.console.config.set.language.description
**container**  |
[container:debug](container-debug.md) | Mostra el serveis actuals de l'aplicació.
**create**  |
[create:nodes](create-nodes.md) | Crear nodes dummy per la teva aplicació Drupal 8.
[create:terms](create-terms.md) | Crear termes dummy per la teva aplicació Drupal 8.
[create:users](create-users.md) | Crear usuaris dummy per la teva aplicació Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crear vocabulari dummy per la teva aplicació Drupal 8.
**cron**  |
[cron:debug](cron-debug.md) | Llista de mòduls que implementen una crida al cron
[cron:execute](cron-execute.md) | Executar implementació de cron per mòdul o executar-los tots
[cron:release](cron-release.md) | Desbloquejar el cron del sistema per tornar a executar-lo
**database**  |
[database:client](database-client.md) | Llançar un client de base de dades si està disponible
[database:connect](database-connect.md) | Llançar un client de base de dades si està disponible
[database:dump](database-dump.md) | Volcat d'estructura, continguts i taules de la base de dades MySQL
[database:log:clear](database-log-clear.md) | Eliminar esdeveniments de la taula DBLog, filtre disponible
[database:log:debug](database-log-debug.md) | Mostrar el registre d'esdeveniments actual de l'aplicació
[database:restore](database-restore.md) | Restaurar l'estructura, continguts i taules de la base de dades MySQL
[database:table:debug](database-table-debug.md) | Mostra les taules d'una base de dades.
[database:table:drop](database-table-drop.md) | Esborrar les taules d'una base de dades.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveïdor d'Autenticació
[generate:command](generate-command.md) | Generar comandaments per la consola
[generate:controller](generate-controller.md) | Generar i registrar un controlador
[generate:doc:dash](generate-doc-dash.md) | Generar documentació per els comandaments
[generate:doc:gitbook](generate-doc-gitbook.md) | Generar documentació per els comandaments
[generate:entity:bundle](generate-entity-bundle.md) | Generar un nou tipus de contingut (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generar una nova entitat de continguts
[generate:entity:content](generate-entity-content.md) | Generar una entitat de contingut
[generate:event:subscriber](generate-event-subscriber.md) | Generar subscriptor d'esdeveniments
[generate:form](generate-form.md) | Generar un nou "FormBase"
[generate:form:alter](generate-form-alter.md) | Generar una implementació de hook_form_alter() o hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generar un nou "ConfigFormBase"
[generate:module](generate-module.md) | Generar mòdul
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | commands.generate.plugin.block.description
[generate:plugin:condition](generate-plugin-condition.md) | Generar un connector de condició (Plugin condition)
[generate:plugin:field](generate-plugin-field.md) | Generar connectors de tipus de camp, plugin i formatador
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Genera un  plugin formatador de camp.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generar plugin de tipus de camp.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generar plugin de widget de camp.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generar plugin d'efecte d'imatge.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generar plugin formatador de camp.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generar plugin de recursos Rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generar un plugin d'acció de regla
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generar un tipus de plugin amb descobriment d'anotació
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Genera un tipus de plugin amb descobriment de Yaml
[generate:plugin:views:field](generate-plugin-views-field.md) | Generar un plugin de camp de vista predeterminat.
[generate:profile](generate-profile.md) | Generar un perfil.
[generate:routesubscriber](generate-routesubscriber.md) | Generar una ruta de subcriptor (RouteSubscriber)
[generate:service](generate-service.md) | Generar servei
[generate:theme](generate-theme.md) | Generar un tema.
**locale**  |
[locale:language:add](locale-language-add.md) | Afegir un idioma per el teu lloc web
[locale:language:delete](locale-language-delete.md) | Esborrar un idioma del teu lloc web
[locale:translation:status](locale-translation-status.md) | LLista les actualitzacions de traduccions disponibles
**migrate**  |
[migrate:debug](migrate-debug.md) |  Mostrar la migració actual disponible per l'aplicació
[migrate:execute](migrate-execute.md) | Executar la migració disponible per l'aplicació
[migrate:setup](migrate-setup.md) | Carregar i crear migracions proveïdes per una base de dades heretada
**module**  |
[module:debug](module-debug.md) | Mostrar els mòduls disponibles per l'aplicació
[module:download](module-download.md) | Descarregar mòduls a la aplicació
[module:install](module-install.md) | Instal·lar mòdul en l'aplicació
[module:uninstall](module-uninstall.md) | Desintal·lar mòdul(s) en l'aplicació
**multisite**  |
[multisite:debug](multisite-debug.md) | Mostra tots el multisites disponibles al sistema
**rest**  |
[rest:debug](rest-debug.md) | Mostra el recurs Rest actual per l'aplicació
[rest:disable](rest-disable.md) | Deshabilitar el recurs Rest per l'aplicació
[rest:enable](rest-enable.md) | Habilitar un resurs Rest per l'aplicació
**router**  |
[router:debug](router-debug.md) | Mostrar les rutes actuals per l'aplicació
[router:rebuild](router-rebuild.md) | Reconstruir rutes per l'aplicació
**settings**  |
[settings:debug](settings-debug.md) | Displays current key:value on settings file.
**site**  |
[site:debug](site-debug.md) | List all known local and remote sites.
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Create a new Drupal project
[site:status](site-status.md) | View current Drupal Installation status
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:override](state-override.md) | Override a State key.
**test**  |
[test:debug](test-debug.md) | List Test Units available for the application.
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:debug](theme-debug.md) | Displays current themes for the application
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Install theme or themes in the application
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clenaup translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Display current updates available for the application
[update:execute](update-execute.md) | Execute a specific Update N function in a module, or execute all
**user**  |
[user:debug](user-debug.md) | Displays current users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Clear login failed attempts for an account.
[user:login:url](user-login-url.md) | Returns a one-time user login url.
[user:password:hash](user-password-hash.md) | Generate a hash from a plaintext password.
[user:password:reset](user-password-reset.md) | Reset password for a specific user.
**views**  |
[views:debug](views-debug.md) | Display current views resources for the application
[views:disable](views-disable.md) | Disable a View
[views:enable](views-enable.md) | Enable a View
**yaml**  |
[yaml:diff](yaml-diff.md) | Compare two YAML files in order to find differences between them.
[yaml:merge](yaml-merge.md) | Merge one or more YAML files in a new YAML file. Latest values are preserved.
[yaml:split](yaml-split.md) | Split a YAML file using indent as separator criteria
[yaml:update:key](yaml-update-key.md) | Replace a YAML key in a YAML file.
[yaml:update:value](yaml-update-value.md) | Update a value for a specific key in a YAML file.

## Opcions disponibles
Opció | Detalls
-------|-------------
--help | Mostra aquest missatge d'ajuda
--quiet | No mostrar cap missatge
--verbose | Augmentar el detall dels missatges: 1 per una sortida normal, 2 per obtenir més detall i 3 per depurar
--version | Mostra la versió d'aquesta applicació
--ansi | Forçar la sortida ANSI
--no-ansi | Deshabilitar la sortida ANSI
--no-interaction | No preguntar res de forma interactiva
--env | Nom de l'entorn.
--root | Definir la ruta arrel de Drupal on s'executaran els comandaments
--no-debug | Desactivar el mode de depuració (debug).
--learning | Generar codi detalladament (verbose).
--generate-chain | Imprimir les opcions d'execució i els arguments com una sortida de YAML per ser utilitzats amb el comandament "chain".
--generate-inline | Imprimir les opcions d'execució i els arguments com inserits (inline) per ser utilitzats en un futur
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Skip confirmation and proceed

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
