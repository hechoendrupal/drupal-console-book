# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Alapvető információkat jelenít meg a Drupal Console projektről
[chain](chain.md) | Chain parancs végrehajtása
[check](check.md) | System requirement checker
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | A rendelkezésre álló parancsok listázása
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | A PHP beépített webkiszolgálójának futtatása
**cache**  |
[cache:rebuild](cache-rebuild.md) | A webhely összes gyorsítótárának újraépítése és törlése.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Az aktív konfigurációt egy könyvtárral összehasonlítva az eltérő konfigurációs elemek.
[config:edit](config-edit.md) | Szerkeszteni kell a kiválasztott konfigurációt.
[config:export](config-export.md) | Aktuális alkalmazáskonfiguráció exportálása.
[config:export:content:type](config-export-content-type.md) | Adott tartalomtípus és mezőinek exportálása.
[config:export:single](config-export-single.md) | Egyetlen konfigurációs fájl exportálása yml-fájlként.
[config:export:view](config-export-view.md) | Nézet exportálása YAML-formátumban egy megadott modulba, hogy újra lehessen használni más weboldalon.
[config:import](config-import.md) | Konfiguráció importálása az aktuális alkalmazásba.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Az aktív konfiguráció értékének felülbírálása.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Teszttartalom létrehozása egy Drupal 8 alkalmazáshoz.
[create:terms](create-terms.md) | Tesztkifejezések létrehozása egy Drupal 8 alkalmazáshoz.
[create:users](create-users.md) | Tesztfelhasználók létrehozása egy Drupal 8 alkalmazáshoz.
[create:vocabularies](create-vocabularies.md) | Tesztszótárak létrehozása egy Drupal 8 alkalmazáshoz.
**cron**  |
[cron:execute](cron-execute.md) | Cron megvalósítások végrehajtása modul szerint, vagy az összes cron metódus végrehajtása
[cron:release](cron-release.md) | Cron rendszerzár feloldása a cron újbóli futtatásához
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Adatbázisügyfél indítása, ha az elérhető
[database:connect](database-connect.md) | Megjeleníti az adatbázis-kapcsolatot
[database:drop](database-drop.md) | Egy adatbázis összes táblájának eldobása.
[database:dump](database-dump.md) | Adatbázis szerkezetének és tartalmának kiíratása
[database:log:clear](database-log-clear.md) | Események eltávolítása a DBLog táblából, rendelkezésre állnak szűrők
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Adatbázis szerkezetének és tartalmának visszaállítása.
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | Rendelkezésre álló láncolt fájlok felsorolása.
[debug:config](debug-config.md) | Aktuális konfiguráció megjelenítése.
[debug:config:settings](debug-config-settings.md) | A beállításfájl aktuális kulcs:érték beállításainak megjelenítése.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Egy alkalmazás aktuális szolgáltatásait jeleníti meg.
[debug:cron](debug-cron.md) | Cron metódust megvalósító modulok listája
[debug:database:log](debug-database-log.md) | Az alkalmazás aktuális naplóeseményeinek megjelenítése
[debug:database:table](debug-database-table.md) | Adott adatbázis összes táblájának megjelenítése.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Az elérhető aktuális költöztetések megjelenítése
[debug:module](debug-module.md) | Az alkalmazáshoz elérhető aktuális modulok megjelenítése
[debug:multisite](debug-multisite.md) | A rendszeren elérhető multisite-ok listázása
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Aktuális REST-erőforrás megjelenítése
[debug:router](debug-router.md) | Megjeleníti az alkalmazás aktuális útvonalait
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | Minden ismert helyi és távoli webhely listázása.
[debug:state](debug-state.md) | Az aktuális állapotkulcsok megjelenítése.
[debug:test](debug-test.md) | Az alkalmazás egységtesztjeinek listázása.
[debug:theme](debug-theme.md) | Megjeleníti az alkalmazás aktuális sminkjeit
[debug:update](debug-update.md) | Az alkalmazás jelenleg elérhető frissítéseinek megjelenítése
[debug:user](debug-user.md) | Megjeleníti az aktuális felhasználókat
[debug:views](debug-views.md) | Alkalmazás aktuális views erőforrásainak megjelenítése
[debug:views:plugins](debug-views-plugins.md) | Display current views plugins for the application
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
[entity:delete](entity-delete.md) | Delete an specific entity
**extend**  |
[extend:example:one](extend-example-one.md) | Drupal Console extend example
[extend:example:two](extend-example-two.md) | Drupal Console extend example
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Hitelesítésszolgáltató létrehozása
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Parancsok létrehozása a konzolhoz.
[generate:controller](generate-controller.md) | Kontroller létrehozása és regisztrálása
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | Új tartalomtípus létrehozása (tartalom / mezőköteg)
[generate:entity:config](generate-entity-config.md) | Új konfigurációs entitás létrehozása
[generate:entity:content](generate-entity-content.md) | Új tartalom entitás létrehozása
[generate:event:subscriber](generate-event-subscriber.md) | Esemény-előfizető létrehozása
[generate:form](generate-form.md) | Új "%s" létrehozása
[generate:form:alter](generate-form-alter.md) | A hook_form_alter() vagy hook_form_FORM_ID_alter megvalósításának létrehozása
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Modul létrehozása.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | Blokk bővítmény létrehozása
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Feltételbővítmény létrehozása.
[generate:plugin:field](generate-plugin-field.md) | Mezőtípus, felületi elem és formázó bővítmények létrehozása.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Mezőformázó bővítmény létrehozása
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Mezőtípus bővítmény létrehozása
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Mező felületi elem bővítmény létrehozása
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Képhatás bővítmény létrehozása
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Képformázó bővítmény létrehozása.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | REST-erőforrás bővítmény létrehozása
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Szabályművelet bővítmény létrehozása
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Bővítménytípus létrehozása magyarázatészleléssel
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Bővítménytípus létrehozása YAML-észleléssel
[generate:plugin:views:field](generate-plugin-views-field.md) | Egyéni nézetmező bővítmény létrehozása.
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | Profil létrehozása.
[generate:routesubscriber](generate-routesubscriber.md) | RouteSubscriber létrehozása
[generate:service](generate-service.md) | Szolgáltatás létrehozása
[generate:theme](generate-theme.md) | Smink létrehozása.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | A webhely által támogatott nyelv hozzáadása
[locale:language:delete](locale-language-delete.md) | A webhely által támogatott nyelv törlése
[locale:translation:status](locale-translation-status.md) | Rendelkezésre álló fordítási frissítések listázása
**migrate**  |
[migrate:execute](migrate-execute.md) | Az alkalmazáshoz elérhető költöztetés végrehajtása
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Adott örökölt adatbázis fontos költöztetéseinek betöltése és létrehozása
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Modul vagy modulok letöltése
[module:install](module-install.md) | Modul vagy modulok telepítése
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Modul vagy modulok eltávolítása
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | REST-erőforrás letiltása
[rest:enable](rest-enable.md) | Az alkalmazás REST-erőforrásának engedélyezése
**router**  |
[router:rebuild](router-rebuild.md) | Az alkalmazás útvonalainak újraépítése
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Drupal projekt telepítése
[site:maintenance](site-maintenance.md) | Webhely karbantartási módba állítása
[site:mode](site-mode.md) | Rendszerteljesítmény beállításának átváltása
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Aktuális Drupal-telepítés állapotának megtekintése
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Állapotkulcs felülbírálása.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Egységteszt futtatása az alkalmazás számára elérhető tesztek közül
**theme**  |
[theme:download](theme-download.md) | Smink letöltése az alkalmazásban
[theme:install](theme-install.md) | Smink vagy sminkek telepítése az alkalmazásba
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Az alkalmazás sminkjének vagy sminkjeinek eltávolítása
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Egy modul adott Update N függvényének végrehajtása, vagy az összes végrehajtása
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Felhasználók törlése
[user:login:clear:attempts](user-login-clear-attempts.md) | Egy fiók sikertelen bejelentkezési kísérleteinek törlése.
[user:login:url](user-login-url.md) | Egyszer használatos felhasználói bejelentkezési URL-címet ad vissza.
[user:password:hash](user-password-hash.md) | Ellenőrzőösszeg előállítása sima szöveges jelszóból.
[user:password:reset](user-password-reset.md) | Adott felhasználó jelszavának alaphelyzetbe állítása.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Nézet letiltása
[views:enable](views-enable.md) | Nézet engedélyezése

## Available options
Option | Details
-------|-------------
--help | A súgóüzenet megjelenítése
--quiet | Ne írjon ki semmilyen üzenetet
--verbose | Az üzenetek részletességi szintjének növelése: 1: normális kimenet, 2: részletesebb kimenet, és 3: hibakeresés
--version | Az alkalmazás verziójának megjelenítése
--ansi | ANSI kimenet kényszerítése
--no-ansi | ANSI kimenet tiltása
--no-interaction | Ne tegyen fel semmilyen kérdést
--env | A környezet neve
--root | A parancs végrehajtásakor használt Drupal gyökérkönyvtárt adja meg
--debug | application.options.debug
--learning | Részletes kódkimenet létrehozása
--generate-chain | A parancspbeállításokat és argumentumokat a chain parancsban használandó yaml-kimenetként jeleníti meg
--generate-inline | A parancsbeállításokat és argumentumokat beágyazott parancsként jeleníti meg
--generate-doc | A parancsbeállításokat és argumentumokat markdown szövegként jeleníti meg
--target | A kezelni kívánt webhely neve (helyi vagy távoli webhelyek esetén)
--uri | A használandó Drupal webhely URI-címe (multisite vagy másodlagos porton futó környezetek esetén)
--yes | Megerősítés kihagyása és a művelet folytatása

## Available arguments
Argument | Details
---------|-------------
command | A végrehajtandó parancs
