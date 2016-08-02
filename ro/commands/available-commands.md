# Comenzi pentru Consola de Drupal disponibile

**Notă:** Comenzile Consolei de Drupal *trebuie* să fie rulate din rădăcina instalării Drupal 8.

Comanda Consolei Drupal | Detalii
------------ | -------------
[about](about.md) | Afișează informațiile de bază despre proiectul Drupal Console
[chain](chain.md) | Execuție comandă înlănțuită
[check](check.md) | System requirement checker
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Listele de comenzi
[self-update](self-update.md) | Update project to the latest version.
[server](server.md) | Runs PHP built-in web server
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | Displays breakpoints available in application
**cache**  |
[cache:context:debug](cache-context-debug.md) | Displays current cache context for the application.
[cache:rebuild](cache-rebuild.md) | Reconstruiți și curățați tot cache-ul.
**chain**  |
[chain:debug](chain-debug.md) | List available chain files.
**config**  |
[config:debug](config-debug.md) | Afișează configurarea curentă.
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Editează configurarea selectată.
[config:export](config-export.md) | Exportă configurările curente ale aplicației.
[config:export:content:type](config-export-content-type.md) | Exportă un anumit tip de conținut și câmpurile aferente.
[config:export:view](config-export-view.md) | Exportă un view în format YAML în cadrul unui modul pentru a fi reutilizat într-un alt website.
[config:import](config-import.md) | Importă configurarea pentru aplicația curentă.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Suprascrie valoarea de configurare în configurarea activă.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Afișează serviciile curente pentru o aplicație.
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | Lista modulelor ce implementează un cron
[cron:execute](cron-execute.md) | Execută cron-ul direct dintr-un modul sau din toate
[cron:release](cron-release.md) | Lansează sistemul de blocare pentru a repermite reluarea rulării cron-ului
**database**  |
[database:client](database-client.md) | Lansează un client DB dacă acesta este disponibil
[database:connect](database-connect.md) | Lansează un client DB dacă acesta este disponibil
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Descărcați structura și conținutul bazei de date MySQL și tabelele acesteia
[database:log:clear](database-log-clear.md) | Eliminați evenimentele din tabelul DBLog, sunt disponibile filtre
[database:log:debug](database-log-debug.md) | Afișează evenimentele curente, de intrare în jurnal, pentru aplicație
[database:restore](database-restore.md) | Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
**devel**  |
[devel:dumper](devel-dumper.md) | Change the devel dumper plugin
**event**  |
[event:debug](event-debug.md) | Display current events 
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
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | Displays libraries available in application
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Afisează migrațiunea curentă accesibilă pentru aplicație
[migrate:execute](migrate-execute.md) | Execută o migraţie disponibilă pentru aplicaţie
**module**  |
[module:debug](module-debug.md) | Afişează Modulele curente pentru aplicaţie
[module:download](module-download.md) | Descarcă modulul sau modulele pentru aplicație
[module:install](module-install.md) | Instaleaza Module
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Dezinstalează un modul sau mai multe din aplicaţie.
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | Listează toate multi siturile disponibile în sistem
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**queue**  |
[queue:debug](queue-debug.md) | Display the queues of your application
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:debug](rest-debug.md) | Afişează resursele REST curente.
[rest:disable](rest-disable.md) | Dezactiveaza o resursă REST
[rest:enable](rest-enable.md) | Activează o resursă REST pentru aplicaţie.
**router**  |
[router:debug](router-debug.md) | Afişează rutele curente
[router:rebuild](router-rebuild.md) | Reconstruieşte o rută
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Listează toate siturile locale sau la distanță.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Instalează un proiect Drupal
[site:maintenance](site-maintenance.md) | Activează modul de mentenanţă
[site:mode](site-mode.md) | Schimbă configurarile de performanţă ale sistemului
[site:new](site-new.md) | Crează un proiect Drupal nou.
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Vizualizează statutul de instalare (Drupal Installation status)
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Override a State key.
**test**  |
[test:debug](test-debug.md) | Afişează testele accesibile
[test:run](test-run.md) | Execută un test dintre testele disponibile in aplicaţie.
**theme**  |
[theme:debug](theme-debug.md) | Afișează temele curente pentru aplicație
[theme:download](theme-download.md) | Descarcă tema în aplicație
[theme:install](theme-install.md) | Instalează tema sau temele în aplicație
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Dezinstalează tema sau temele din aplicație
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Afişează actualizările disponibile pentru aplicaţie.
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Execută o funcţie specifică Update N dintr-un modul sau execută-le pe toate
**user**  |
[user:debug](user-debug.md) | Displays current users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Şterge autentificările eşuate pentru un cont.
[user:login:url](user-login-url.md) | Returneaza un URL de logare care poate fi folosit o singură dată.
[user:password:hash](user-password-hash.md) | Generează un hash dintr-o parolă de tip text.
[user:password:reset](user-password-reset.md) | Resetează parola pentru un utilizator.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:debug](views-debug.md) | Afişează resursele curente ale views-ului pentru aplicație.
[views:disable](views-disable.md) | Dezactivează un View
[views:enable](views-enable.md) | Activează un View
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | Compară două fişiere YAML pentru a determina diferenţele dintre acestea.
[yaml:merge](yaml-merge.md) | Uneşte doua sau mai multe fişiere de tip YAML într-un nou fişier de tip YAML. Ultimele valori sunt păstrate.
[yaml:split](yaml-split.md) | Separă un fişier YAML folosind indentarea ca şi criteriu de separare.
[yaml:update:key](yaml-update-key.md) | Înlocuieşte o cheie de tip YAML într-un fişier te tip YAML.
[yaml:update:value](yaml-update-value.md) | Actualizează valoarea unei chei specifice într-un fişier YAML.

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>"%s"</info> versiunea <comment>"%s"</comment>
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | Numele mediului de lucru.
--root | Definiți rădăcina Drupal care va fi folosită la executarea comenzilor
--no-debug | Oprește modul de depanare.
--learning | Generarea unui cod verbal.
--generate-chain | Printează opțiunile și argumentele de execuție în format yaml pentru a fi folosit în comandă înlănțuită
--generate-inline | Printează opțiunile și argumentele de execuție în apel inline pentru a fi folosit pe viitor
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI-ul sitului Drupal care va fi folosit (pentru medii multi-sit sau când rulează pe un port alternativ)
--yes | Skip confirmation and proceed

## Argumente disponibile
Argument | Detalii
---------|-------------
command | The command to execute
