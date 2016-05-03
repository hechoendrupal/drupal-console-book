# Rendelkezésre álló Drupal Console parancsok

**Megjegyzés:** A Drupal Console parancsokat a Drupal 8 telepítési gyökérkönyvtárából *kell* futtatni.

Drupal Console parancs | Részletek
------------ | -------------
[about](about.md) | Alapvető információkat jelenít meg a Drupal Console projektről
[chain](chain.md) | Chain parancs végrehajtása
[check](check.md) | commands.check.description
[help](help.md) | Displays help for a command
[init](init.md) | commands.init.description
[list](list.md) | A rendelkezésre álló parancsok listázása
[self-update](self-update.md) | Projekt frissítése a legújabb verzióra.
[server](server.md) | A PHP beépített webkiszolgálójának futtatása
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | commands.breakpoints.debug.description
**cache**  |
[cache:rebuild](cache-rebuild.md) | A webhely összes gyorsítótárának újraépítése és törlése.
**chain**  |
[chain:debug](chain-debug.md) | Rendelkezésre álló láncolt fájlok felsorolása.
**config**  |
[config:debug](config-debug.md) | Aktuális konfiguráció megjelenítése.
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
[config:settings:debug](config-settings-debug.md) | A beállításfájl aktuális kulcs:érték beállításainak megjelenítése.
**container**  |
[container:debug](container-debug.md) | Egy alkalmazás aktuális szolgáltatásait jeleníti meg.
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Teszttartalom létrehozása egy Drupal 8 alkalmazáshoz.
[create:terms](create-terms.md) | Tesztkifejezések létrehozása egy Drupal 8 alkalmazáshoz.
[create:users](create-users.md) | Tesztfelhasználók létrehozása egy Drupal 8 alkalmazáshoz.
[create:vocabularies](create-vocabularies.md) | Tesztszótárak létrehozása egy Drupal 8 alkalmazáshoz.
**cron**  |
[cron:debug](cron-debug.md) | Cron metódust megvalósító modulok listája
[cron:execute](cron-execute.md) | Cron megvalósítások végrehajtása modul szerint, vagy az összes cron metódus végrehajtása
[cron:release](cron-release.md) | Cron rendszerzár feloldása a cron újbóli futtatásához
**database**  |
[database:client](database-client.md) | Adatbázisügyfél indítása, ha az elérhető
[database:connect](database-connect.md) | Megjeleníti az adatbázis-kapcsolatot
[database:drop](database-drop.md) | Egy adatbázis összes táblájának eldobása.
[database:dump](database-dump.md) | Adatbázis szerkezetének és tartalmának kiíratása
[database:log:clear](database-log-clear.md) | Események eltávolítása a DBLog táblából, rendelkezésre állnak szűrők
[database:log:debug](database-log-debug.md) | Az alkalmazás aktuális naplóeseményeinek megjelenítése
[database:restore](database-restore.md) | Adatbázis szerkezetének és tartalmának visszaállítása.
[database:table:debug](database-table-debug.md) | Adott adatbázis összes táblájának megjelenítése.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Hitelesítésszolgáltató létrehozása
[generate:command](generate-command.md) | Parancsok létrehozása a konzolhoz.
[generate:controller](generate-controller.md) | Kontroller létrehozása és regisztrálása
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | DrupalConsole.docset csomag létrehozása a Dash számára
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | Dokumentáció létrehozása a parancsokhoz
[generate:entity:bundle](generate-entity-bundle.md) | Új tartalomtípus létrehozása (tartalom / mezőköteg)
[generate:entity:config](generate-entity-config.md) | Új konfigurációs entitás létrehozása
[generate:entity:content](generate-entity-content.md) | Új tartalom entitás létrehozása
[generate:event:subscriber](generate-event-subscriber.md) | Esemény-előfizető létrehozása
[generate:form](generate-form.md) | Új "FormBase" létrehozása
[generate:form:alter](generate-form-alter.md) | A hook_form_alter() vagy hook_form_FORM_ID_alter megvalósításának létrehozása
[generate:form:config](generate-form-config.md) | Új "ConfigFormBase" létrehozása
[generate:module](generate-module.md) | Modul létrehozása.
[generate:permissions](generate-permissions.md) | Modul engedélyeinek létrehozása
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
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | REST-erőforrás bővítmény létrehozása
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Szabályművelet bővítmény létrehozása
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Bővítménytípus létrehozása magyarázatészleléssel
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Bővítménytípus létrehozása YAML-észleléssel
[generate:plugin:views:field](generate-plugin-views-field.md) | Egyéni nézetmező bővítmény létrehozása.
[generate:profile](generate-profile.md) | Profil létrehozása.
[generate:routesubscriber](generate-routesubscriber.md) | RouteSubscriber létrehozása
[generate:service](generate-service.md) | Szolgáltatás létrehozása
[generate:theme](generate-theme.md) | Smink létrehozása.
**image**  |
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | commands.libraries.debug.description
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
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**rest**  |
[rest:debug](rest-debug.md) | Aktuális REST-erőforrás megjelenítése
[rest:disable](rest-disable.md) | REST-erőforrás letiltása
[rest:enable](rest-enable.md) | Az alkalmazás REST-erőforrásának engedélyezése
**router**  |
[router:debug](router-debug.md) | Megjeleníti az alkalmazás aktuális útvonalait
[router:rebuild](router-rebuild.md) | Az alkalmazás útvonalainak újraépítése
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Minden ismert helyi és távoli webhely listázása.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Drupal projekt telepítése
[site:maintenance](site-maintenance.md) | Webhely karbantartási módba állítása
[site:mode](site-mode.md) | Rendszerteljesítmény beállításának átváltása
[site:new](site-new.md) | Új Drupal projekt létrehozása
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Aktuális Drupal-telepítés állapotának megtekintése
**state**  |
[state:debug](state-debug.md) | Az aktuális állapotkulcsok megjelenítése.
[state:delete](state-delete.md) | Delete State
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
[update:entities](update-entities.md) | Applying Entity Updates
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
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | Két YAML-fájl összehasonlítása a közöttük lévő különbségek megkereséséhez.
[yaml:merge](yaml-merge.md) | YAML-fájlok összevonása egy új YAML-fájlba. A legfrissebb értékek maradnak meg.
[yaml:split](yaml-split.md) | YAML-fájl felosztása a behúzást elválasztási feltételként használva
[yaml:update:key](yaml-update-key.md) | YAML-kulcs lecserélése egy YAML-fájlban.
[yaml:update:value](yaml-update-value.md) | A YAML-fájl adott kulcsához tartozó érték frissítése.

## Rendelkezésre álló beállítások
Beállítás | Részletek
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
--no-debug | Kikapcsolja a hibakeresési módot
--learning | Részletes kódkimenet létrehozása
--generate-chain | A parancspbeállításokat és argumentumokat a chain parancsban használandó yaml-kimenetként jeleníti meg
--generate-inline | A parancsbeállításokat és argumentumokat beágyazott parancsként jeleníti meg
--generate-doc | A parancsbeállításokat és argumentumokat markdown szövegként jeleníti meg
--target | A kezelni kívánt webhely neve (helyi vagy távoli webhelyek esetén)
--uri | A használandó Drupal webhely URI-címe (multisite vagy másodlagos porton futó környezetek esetén)
--yes | Megerősítés kihagyása és a művelet folytatása

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
command | A végrehajtandó parancs
