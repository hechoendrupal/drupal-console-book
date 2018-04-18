# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Afișează informațiile de bază despre proiectul Drupal Console
[chain](chain.md) | Execuție comandă înlănțuită
[check](check.md) | System requirement checker
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Listele de comenzi
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruiți și curățați tot cache-ul.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Editează configurarea selectată.
[config:export](config-export.md) | Exportă configurările curente ale aplicației.
[config:export:content:type](config-export-content-type.md) | Exportați un anumit tip de conținut și câmpurile aferente acestuia.
[config:export:single](config-export-single.md) | Exportați o configurare unică ca și un fișier yml .
[config:export:view](config-export-view.md) | Exportă un view în format YAML în interiorul unui modul furnizat pentru a-l reutiliza în alt sit web.
[config:import](config-import.md) | Importă configurarea pentru aplicația curentă.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Suprascrie valoarea de configurare în configurarea activă.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:execute](cron-execute.md) | Execută cron-ul direct dintr-un modul sau din toate
[cron:release](cron-release.md) | Lansează sistemul de blocare pentru a repermite reluarea rulării cron-ului
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Lansează un client DB dacă acesta este disponibil
[database:connect](database-connect.md) | Lansează un client DB dacă acesta este disponibil
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Descărcați structura și conținutul bazei de date MySQL și tabelele acesteia
[database:log:clear](database-log-clear.md) | Eliminați evenimentele din tabelul DBLog, sunt disponibile filtre
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | Afișează configurarea curentă.
[debug:config:settings](debug-config-settings.md) | Displays current key:value on settings file.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Afișează serviciile curente pentru o aplicație.
[debug:cron](debug-cron.md) | Lista modulelor ce implementează un cron
[debug:database:log](debug-database-log.md) | Afișează evenimentele curente, de intrare în jurnal, pentru aplicație
[debug:database:table](debug-database-table.md) | Show all tables in a given database.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Afisează migrațiunea curentă accesibilă pentru aplicație
[debug:module](debug-module.md) | Afişează Modulele curente pentru aplicaţie
[debug:multisite](debug-multisite.md) | Listează toate multi siturile disponibile în sistem
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Afişează resursele REST curente.
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Afişează rutele curente
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | Listează toate siturile locale sau la distanță.
[debug:state](debug-state.md) | Show the current State keys.
[debug:test](debug-test.md) | Afişează testele accesibile
[debug:theme](debug-theme.md) | Afișează temele curente pentru aplicație
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | Afişează actualizările disponibile pentru aplicaţie.
[debug:user](debug-user.md) | Displays current users for the application
[debug:views](debug-views.md) | Afişează resursele curente ale views-ului pentru aplicație.
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
[generate:authentication:provider](generate-authentication-provider.md) | Generează un "Authentication Provider"
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Generează comenzi pentru consolă.
[generate:controller](generate-controller.md) | Generează și Înregistrează un controller
[generate:entity:bundle](generate-entity-bundle.md) | Generează un tip de conținut nou (nod / entitate)
[generate:entity:config](generate-entity-config.md) | Generează o entitate de configurare nouă
[generate:entity:content](generate-entity-content.md) | Generează o entitate de conținut nouă
[generate:event:subscriber](generate-event-subscriber.md) | Generează un abonat la eveniment
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generează o implementare a hook_form_alter() sau hook_form_FORM_ID_alter()
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Generează un modul.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generează un Plugin de tip bloc
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Generează o condiție pentru extensie.
[generate:plugin:field](generate-plugin-field.md) | Generează extensiile: tipul de câmp, widget-ul si formatare.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generează extensia de formatare a câmpului.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generează extensia de tip câmp.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generează extensia de widget pentru câmp.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generează un plugin pentru efecte de imagini.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generează un plugin de formatare a imaginii.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generează un plugin de tip resursă REST
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generează un plugin care implementează o acţiune de rules
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generează un tip de plugin cu descoperire de adnotaţii
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generează un tip de plugin cu descoperire de YAML.
[generate:plugin:views:field](generate-plugin-views-field.md) | Generează o extensie custom de views field.
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generează un RouteSubscriber
[generate:service](generate-service.md) | Genereaza un serviciu
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Generează o temă.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Adaugă o limbă ce va avea suport pe situl dvs.
[locale:language:delete](locale-language-delete.md) | Ștergeți o limbă ce are suport pe situl dvs.
[locale:translation:status](locale-translation-status.md) | Listează actualizările de traducere disponibile
**migrate**  |
[migrate:execute](migrate-execute.md) | Execută o migraţie disponibilă pentru aplicaţie
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Încărcați și creați migrațiunile relevante pentru o bază de date furnizată
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Descarcă modulul sau modulele pentru aplicație
[module:install](module-install.md) | Instaleaza Module
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Dezinstalează un modul sau mai multe din aplicaţie.
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:disable](rest-disable.md) | Dezactiveaza o resursă REST
[rest:enable](rest-enable.md) | Activează o resursă REST pentru aplicaţie.
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Reconstruieşte o rută
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Instalează un proiect Drupal
[site:maintenance](site-maintenance.md) | Activează modul de mentenanţă
[site:mode](site-mode.md) | Schimbă configurarile de performanţă ale sistemului
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Vizualizează statutul de instalare (Drupal Installation status)
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Override a State key.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Execută un test dintre testele disponibile in aplicaţie.
**theme**  |
[theme:download](theme-download.md) | Descarcă tema în aplicație
[theme:install](theme-install.md) | Instalează tema sau temele în aplicație
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Dezinstalează tema sau temele din aplicație
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Execută o funcţie specifică Update N dintr-un modul sau execută-le pe toate
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Şterge autentificările eşuate pentru un cont.
[user:login:url](user-login-url.md) | Returneaza un URL de logare care poate fi folosit o singură dată.
[user:password:hash](user-password-hash.md) | Generează un hash dintr-o parolă de tip text.
[user:password:reset](user-password-reset.md) | Resetează parola pentru un utilizator.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Dezactivează un View
[views:enable](views-enable.md) | Activează un View

## Available options
Option | Details
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
--debug | Switches on debug mode
--learning | Generarea unui cod verbal.
--generate-chain | Printează opțiunile și argumentele de execuție în format yaml pentru a fi folosit în comandă înlănțuită
--generate-inline | Printează opțiunile și argumentele de execuție în apel inline pentru a fi folosit pe viitor
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI-ul sitului Drupal care va fi folosit (pentru medii multi-sit sau când rulează pe un port alternativ)
--yes | Skip confirmation and proceed

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
