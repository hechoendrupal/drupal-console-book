# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
[about](about.md) | Alapinformáció listázása a Drupal Console projektről
[chain](chain.md) | Parancsláncsor végrehajtása
[help](help.md) | Displays help for a command
[settings:init](settings-init.md) | Copy configuration files to user home directory.
[list](list.md) | A rendelkezésre álló parancsok listázása
[server](server.md) | A PHP beépített webkiszolgálójának futtatása
**cache**  |
[cache:rebuild](cache-rebuild.md) | Minden gyorsítótár újraépítése és törlése.
**config**  |
[config:debug](config-debug.md) | Jelenlegi beállítások megjelenítése.
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Kiválasztott beállítások szerkesztése.
[config:export](config-export.md) | Jelenlegi alkalmazás beállításainak exportálása.
[config:export:content:type](config-export-content-type.md) | Bizonyos tipusú tartalom és ennek a mezőinek az exportálása.
[config:export:single](config-export-single.md) | Egyetlen konfiguráció exportálása yml fájlként.
[config:export:view](config-export-view.md) | Exportáljon egy view-t YAML formátumban, egy adott modulon belül amit más siteokon újrahasználhat.
[config:import](config-import.md) | Konfiguráció importálása az aktuális aplikációba.
[config:import:single](config-import-single.md) | Importálja a kijelölt konfigurációt.
[config:override](config-override.md) | Beállítás felülírása.
[config:settings:debug](config-settings-debug.md) | A settings fájl aktuális kulcs:érték beállításainak megjelenítése.
**container**  |
[container:debug](container-debug.md) | Alkalmazáshoz tartozó service megjelenítése.
**create**  |
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | Modulok listája amelyek implementálják a cront
[cron:execute](cron-execute.md) | Cron megvalósitás futtatása egy bizonyos modulból vagy az összesből
[cron:release](cron-release.md) | Cron rendszer zárolás feloldása ahhoz hogy a cron újrafusson
**database**  |
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Launch a DB client if it's available
[database:dump](database-dump.md) | Dump structure and contents of MySQL databases and tables
[database:log:clear](database-log-clear.md) | Remove events from DBLog table, filters are available
[database:log:debug](database-log-debug.md) | Display current log events for the application
[database:restore](database-restore.md) | Restore structure and contents of MySQL databases and tables
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
[database:table:drop](database-table-drop.md) | Drop all tables in a given database.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Authentication Provider létrehozása
[generate:command](generate-command.md) | Console parancsok létrehozása.
[generate:controller](generate-controller.md) | Controller létrehozása és regisztrálása
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Új "FormBase" létrehozása
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Új "ConfigFormBase" létrehozása
[generate:module](generate-module.md) | Modul létrehozása.
[generate:permissions](generate-permissions.md) | Modul jogosultságok létrehozása
[generate:plugin:block](generate-plugin-block.md) | Plugin block létrehozása
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Kép hatás beépülő létrehozása.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | REST erőforrás beépülő létrehozása
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Service létrehozása
[generate:theme](generate-theme.md) | Generate a theme.
**locale**  |
[locale:language:add](locale-language-add.md) | A webhely által támogatott nyelv hozzáadása
[locale:language:delete](locale-language-delete.md) | A webhely által támogatott nyelv törlése
[locale:translation:status](locale-translation-status.md) | Rendelkezésre álló fordítási frissítések listázása
**migrate**  |
[migrate:debug](migrate-debug.md) | Az elérhető aktuális költöztetések megjelenítése
[migrate:execute](migrate-execute.md) | Az alkalmazáshoz elérhető költöztetés végrehajtása
[migrate:setup](migrate-setup.md) | Adott örökölt adatbázis fontos költöztetéseinek betöltése és létrehozása
**module**  |
[module:debug](module-debug.md) | Az alkalmazáshoz elérhető aktuális modulok megjelenítése
[module:download](module-download.md) | Modul vagy modulok letöltése
[module:install](module-install.md) | Modul vagy modulok telepítése
[module:uninstall](module-uninstall.md) | Modul vagy modulok eltávolítása
**multisite**  |
[multisite:debug](multisite-debug.md) | A rendszeren elérhető multisite-ok listázása
**rest**  |
[rest:debug](rest-debug.md) | Aktuális REST-erőforrás megjelenítése
[rest:disable](rest-disable.md) | REST-erőforrás letiltása
[rest:enable](rest-enable.md) | Az alkalmazás REST-erőforrásának engedélyezése
**router**  |
[router:debug](router-debug.md) | Megjeleníti az alkalmazás aktuális útvonalait
[router:rebuild](router-rebuild.md) | Az alkalmazás útvonalainak újraépítése
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:init](settings-init.md) | Copy configuration files to user home directory.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Minden ismert helyi és távoli webhely listázása.
[site:install](site-install.md) | Drupal projekt telepítése
[site:maintenance](site-maintenance.md) | Webhely karbantartási módba állítása
[site:mode](site-mode.md) | Rendszerteljesítmény beállításának átváltása
[site:new](site-new.md) | Új Drupal projekt létrehozása
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Aktuális Drupal-telepítés állapotának megtekintése
**state**  |
[state:debug](state-debug.md) | Az aktuális állapotkulcsok megjelenítése.
[state:override](state-override.md) | Állapotkulcs felülbírálása.
**test**  |
[test:debug](test-debug.md) | Az alkalmazás egységtesztjeinek listázása.
[test:run](test-run.md) | Egységteszt futtatása az alkalmazás számára elérhető tesztek közül
**theme**  |
[theme:debug](theme-debug.md) | Megjeleníti az alkalmazás aktuális sminkjeit
[theme:download](theme-download.md) | Smink letöltése az alkalmazásban
[theme:install](theme-install.md) | Smink vagy sminkek telepítése az alkalmazásba
[theme:uninstall](theme-uninstall.md) | Az alkalmazás sminkjének vagy sminkjeinek eltávolítása
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Az alkalmazás jelenleg elérhető frissítéseinek megjelenítése
[update:execute](update-execute.md) | Egy modul adott Update N függvényének végrehajtása, vagy az összes végrehajtása
**user**  |
[user:debug](user-debug.md) | Megjeleníti az aktuális felhasználókat
[user:delete](user-delete.md) | Felhasználók törlése
[user:login:clear:attempts](user-login-clear-attempts.md) | Egy fiók sikertelen bejelentkezési kísérleteinek törlése.
[user:login:url](user-login-url.md) | Egyszer használatos felhasználói bejelentkezési URL-címet ad vissza.
[user:password:hash](user-password-hash.md) | Ellenőrzőösszeg előállítása sima szöveges jelszóból.
[user:password:reset](user-password-reset.md) | Adott felhasználó jelszavának alaphelyzetbe állítása.
**views**  |
[views:debug](views-debug.md) | Alkalmazás aktuális views erőforrásainak megjelenítése
[views:disable](views-disable.md) | Nézet letiltása
[views:enable](views-enable.md) | Nézet engedélyezése
**yaml**  |
[yaml:diff](yaml-diff.md) | Két YAML-fájl összehasonlítása a közöttük lévő különbségek megkereséséhez.
[yaml:merge](yaml-merge.md) | YAML-fájlok összevonása egy új YAML-fájlba. A legfrissebb értékek maradnak meg.
[yaml:split](yaml-split.md) | YAML-fájl felosztása a behúzást elválasztási feltételként használva
[yaml:update:key](yaml-update-key.md) | YAML-kulcs lecserélése egy YAML-fájlban.
[yaml:update:value](yaml-update-value.md) | A YAML-fájl adott kulcsához tartozó érték frissítése.

## Available options
Option | Details
-------|-------------
--help | application.options.help
--quiet | application.options.quiet
--verbose | application.options.verbose
--version | application.options.version
--ansi | application.options.ansi
--no-ansi | application.options.no-ansi
--no-interaction | application.options.no-interaction
--env | application.options.env
--root | application.options.root
--no-debug | application.options.no-debug
--learning | application.options.learning
--generate-chain | application.options.generate-chain
--generate-inline | application.options.generate-inline
--generate-doc | application.options.generate-doc
--target | application.options.target
--uri | application.options.uri
--yes | application.options.yes

## Available arguments
Argument | Details
---------|-------------
command | application.arguments.command
