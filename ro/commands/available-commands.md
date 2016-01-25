# Comenzi pentru Consola de Drupal disponibile

**Notă:** Comenzile Consolei de Drupal *trebuie* să fie rulate din rădăcina instalării Drupal 8.

Comanda Consolei Drupal | Detalii
------------ | -------------
[about](about.md) | Afișează informațiile de bază despre proiectul Drupal Console
[chain](chain.md) | Execuție comandă înlănțuită
[help](help.md) | Displays help for a command
[init](init.md) | Copiază fişierele de configurare în directorul de bază al utilizatorului.
[list](list.md) | Listele de comenzi
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruiți și curățați tot cache-ul.
**config**  |
[config:debug](config-debug.md) | Afișează configurarea curentă.
[config:edit](config-edit.md) | Editează configurarea selectată.
[config:export](config-export.md) | Exportă configurările curente ale aplicației.
[config:export:content:type](config-export-content-type.md) | Exportă un anumit tip de conținut și câmpurile aferente.
[config:export:single](config-export-single.md) | Exportă o singură configurare ca fișier YAML.
[config:export:view](config-export-view.md) | Exportă un view în format YAML în cadrul unui modul pentru a fi reutilizat într-un alt website.
[config:import](config-import.md) | Importă configurarea pentru aplicația curentă.
[config:import:single](config-import-single.md) | Importă configurarea selectată.
[config:override](config-override.md) | Suprascrie valoarea de configurare în configurarea activă.
**container**  |
[container:debug](container-debug.md) | Afișează serviciile curente pentru o aplicație.
**create**  |
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
[database:dump](database-dump.md) | Descărcați structura și conținutul bazei de date MySQL și tabelele acesteia
[database:log:clear](database-log-clear.md) | Eliminați evenimentele din tabelul DBLog, sunt disponibile filtre
[database:log:debug](database-log-debug.md) | Afișează evenimentele curente, de intrare în jurnal, pentru aplicație
[database:restore](database-restore.md) | Restabilește structura și conținutul bazei de date MySQL și ale tabelelor acesteia
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
[database:table:drop](database-table-drop.md) | Drop all tables in a given database.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generează un "Authentication Provider"
[generate:command](generate-command.md) | Generează comenzi pentru consolă.
[generate:controller](generate-controller.md) | Generează și Înregistrează un controller
[generate:doc:dash](generate-doc-dash.md) | Generați pachetul DrupalConsole.docset pentru Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Generează documentațiile pentru Comenzi
[generate:entity:bundle](generate-entity-bundle.md) | Generează un tip de conținut nou (nod / entitate)
[generate:entity:config](generate-entity-config.md) | Generează o entitate de configurare nouă
[generate:entity:content](generate-entity-content.md) | Generează o entitate de conținut nouă
[generate:event:subscriber](generate-event-subscriber.md) | Generează un abonat la eveniment
[generate:form](generate-form.md) | Generează un "FormBase" nou
[generate:form:alter](generate-form-alter.md) | Generează o implementare a hook_form_alter() sau hook_form_FORM_ID_alter()
[generate:form:config](generate-form-config.md) | Generează un "ConfigFormBase" nou
[generate:module](generate-module.md) | Generează un modul.
[generate:permissions](generate-permissions.md) | Generează permisiuni pentru modul
[generate:plugin:block](generate-plugin-block.md) | Generează un Plugin de tip bloc
[generate:plugin:condition](generate-plugin-condition.md) | Generează o condiție pentru extensie.
[generate:plugin:field](generate-plugin-field.md) | Generează extensiile: tipul de câmp, widget-ul si formatare.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generează extensia de formatare a câmpului.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generează extensia de tip câmp.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generează extensia de widget pentru câmp.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generează un plugin pentru efecte de imagini.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generează un plugin de formatare a imaginii.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generează un plugin de tip resursă REST
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generează un plugin care implementează o acţiune de rules
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generează un tip de plugin cu descoperire de adnotaţii
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generează un tip de plugin cu descoperire de YAML.
[generate:plugin:views:field](generate-plugin-views-field.md) | Generează o extensie custom de views field.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generează un RouteSubscriber
[generate:service](generate-service.md) | Genereaza un serviciu
[generate:theme](generate-theme.md) | Generează o temă.
**locale**  |
[locale:language:add](locale-language-add.md) | Adaugă o limbă ce va avea suport pe situl dvs.
[locale:language:delete](locale-language-delete.md) | Ștergeți o limbă ce are suport pe situl dvs.
[locale:translation:status](locale-translation-status.md) | Listează actualizările de traducere disponibile
**migrate**  |
[migrate:debug](migrate-debug.md) | Afisează migrațiunea curentă accesibilă pentru aplicație
[migrate:execute](migrate-execute.md) | Execută o migraţie disponibilă pentru aplicaţie
[migrate:setup](migrate-setup.md) | Încărcați și creați migrațiunile relevante pentru o bază de date furnizată
**module**  |
[module:debug](module-debug.md) | Afişează Modulele curente pentru aplicaţie
[module:download](module-download.md) | Descarcă modulul sau modulele pentru aplicație
[module:install](module-install.md) | Instaleaza Module
[module:uninstall](module-uninstall.md) | Dezinstalează un modul sau mai multe din aplicaţie.
**multisite**  |
[multisite:debug](multisite-debug.md) | Listează toate multi siturile disponibile în sistem
**rest**  |
[rest:debug](rest-debug.md) | Afişează resursele REST curente.
[rest:disable](rest-disable.md) | Dezactiveaza o resursă REST
[rest:enable](rest-enable.md) | Activează o resursă REST pentru aplicaţie.
**router**  |
[router:debug](router-debug.md) | Afişează rutele curente
[router:rebuild](router-rebuild.md) | Reconstruieşte o rută
**settings**  |
[settings:debug](settings-debug.md) | Displays current key:value on settings file.
**site**  |
[site:debug](site-debug.md) | Listează toate siturile locale sau la distanță.
[site:install](site-install.md) | Instalează un proiect Drupal
[site:maintenance](site-maintenance.md) | Activează modul de mentenanţă
[site:mode](site-mode.md) | Schimbă configurarile de performanţă ale sistemului
[site:new](site-new.md) | Crează un proiect Drupal nou.
[site:status](site-status.md) | Vizualizează statutul de instalare (Drupal Installation status)
**state**  |
[state:debug](state-debug.md) | Show the current State keys.
[state:override](state-override.md) | Show the current State keys.
**test**  |
[test:debug](test-debug.md) | Afişează testele accesibile
[test:run](test-run.md) | Execută un test dintre testele disponibile in aplicaţie.
**theme**  |
[theme:debug](theme-debug.md) | Afișează temele curente pentru aplicație
[theme:download](theme-download.md) | Descarcă tema în aplicație
[theme:install](theme-install.md) | Instalează tema sau temele în aplicație
[theme:uninstall](theme-uninstall.md) | Dezinstalează tema sau temele din aplicație
**translation**  |
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
**update**  |
[update:debug](update-debug.md) | Afişează actualizările disponibile pentru aplicaţie.
[update:execute](update-execute.md) | Execută o funcţie specifică Update N dintr-un modul sau execută-le pe toate
**user**  |
[user:debug](user-debug.md) | Displays current users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Şterge autentificările eşuate pentru un cont.
[user:login:url](user-login-url.md) | Returneaza un URL de logare care poate fi folosit o singură dată.
[user:password:hash](user-password-hash.md) | Generează un hash dintr-o parolă de tip text.
[user:password:reset](user-password-reset.md) | Resetează parola pentru un utilizator.
**views**  |
[views:debug](views-debug.md) | Afişează resursele curente ale views-ului pentru aplicație.
[views:disable](views-disable.md) | Dezactivează un View
[views:enable](views-enable.md) | Activează un View
**yaml**  |
[yaml:diff](yaml-diff.md) | Compară două fişiere YAML pentru a determina diferenţele dintre acestea.
[yaml:merge](yaml-merge.md) | Uneşte doua sau mai multe fişiere de tip YAML într-un nou fişier de tip YAML. Ultimele valori sunt păstrate.
[yaml:split](yaml-split.md) | Separă un fişier YAML folosind indentarea ca şi criteriu de separare.
[yaml:update:key](yaml-update-key.md) | Înlocuieşte o cheie de tip YAML într-un fişier te tip YAML.
[yaml:update:value](yaml-update-value.md) | Actualizează valoarea unei chei specifice într-un fişier YAML.

## Opțiuni disponibile
Opțiune | Detalii
-------|-------------
--help | Afișează acest mesaj de ajutor
--quiet | Nu afișa nici un mesaj
--verbose | Crește nivelul de detaliere a mesajelor: 1 pentru o detaliere normală, 2 pentru o detaliere mai amănunțită si 3 pentru depanare
--version | Afișează versiunea aplicației
--ansi | Forțează standardul ANSI
--no-ansi | Dezactivați standardul ANSI
--no-interaction | Nu adresa nici o întrebare interactivă
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
command | Comanda ce urmează a fi executată
