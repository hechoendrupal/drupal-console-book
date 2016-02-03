# Comandaments disponibles de Drupal

**Nota:** Els comandaments de Drupal Console *han* de ser executats a la rel de la'instal·lació de Drupal 8.

Comandaments de Drupal Console | Detalls
------------ | -------------
[about](about.md) | Mostra l'informació bàsica sobre el projecte Drupal Console
[chain](chain.md) | Execució de comandaments en secuència
[help](help.md) | Mostra l'ajuda per un comandament
[settings:init](settings-init.md) | Copiar fitxers de configuració al directori principal de l'usuari.
[list](list.md) | Llista tots els comandaments disponibles
[server](server.md) | Executar servidor PHP integrat
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstrueix i esborra tota la memòria cau (cache) del lloc web.
**config**  |
[config:debug](config-debug.md) | Mostra la configuració actual
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Editar la configuració seleccionada
[config:export](config-export.md) | Exporta la configuració actual de l'aplicació
[config:export:content:type](config-export-content-type.md) | Exporta un tipus de contingut i els seus camps.
[config:export:single](config-export-single.md) | Exportar configuració con a fitxer yml
[config:export:view](config-export-view.md) | Exporta un vista amb el format YAML en un mòdul per reutilitzar-ho en un altre lloc web.
[config:import](config-import.md) | Importa la configuració a l'aplicació actual.
[config:import:single](config-import-single.md) | Importar la configuració seleccionada.
[config:override](config-override.md) | Sobreescriure el valor de la configuració activa.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
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
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
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
[multisite:debug](multisite-debug.md) | Mostra tots el multisites disponibles del sistema
**rest**  |
[rest:debug](rest-debug.md) | Mostra el recurs Rest actual per l'aplicació
[rest:disable](rest-disable.md) | Deshabilitar el recurs Rest per l'aplicació
[rest:enable](rest-enable.md) | Habilitar un recurs Rest per l'aplicació
**router**  |
[router:debug](router-debug.md) | Mostrar les rutes actuals per l'aplicació
[router:rebuild](router-rebuild.md) | Reconstruir rutes per l'aplicació
**settings**  |
[settings:debug](settings-debug.md) | Mostrar la clau actual: valor del fitxer de configuració.
[settings:init](settings-init.md) | Copiar fitxers de configuració al directori principal de l'usuari.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Llista tots els llocs locals i remots coneguts.
[site:install](site-install.md) | Instal·lar un projecte Drupal
[site:maintenance](site-maintenance.md) | Canviar al mode manteniment
[site:mode](site-mode.md) | Canviar la configuració de rendiment del sistema
[site:new](site-new.md) | Crear un nou projecte Drupal
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Veure l'estat actual de l'instal·lació de Drupal
**state**  |
[state:debug](state-debug.md) | Mostrar l'estat actual de les claus.
[state:override](state-override.md) | Anul·lar l'estat de la clau.
**test**  |
[test:debug](test-debug.md) | Llista els Test Units disponibles per l'aplicació.
[test:run](test-run.md) | Executa els Test Units disponibles per l'aplicació
**theme**  |
[theme:debug](theme-debug.md) | Mostra els temes actuals per l'aplicació
[theme:download](theme-download.md) | Descarregar tema per l'aplicació
[theme:install](theme-install.md) | Instal·lar temes per l'aplicació
[theme:uninstall](theme-uninstall.md) | Desinstal·lar temes de l'alicació
**translation**  |
[translation:cleanup](translation-cleanup.md) | Netejar el fitxer de traduccions
[translation:pending](translation-pending.md) | Determinar cadena de traduccions pendent en un idioma o en un fitxer especific d'un idioma
[translation:stats](translation-stats.md) | Generar estadístiques de traduccions
[translation:sync](translation-sync.md) | Sincronitzar fitxer de traduccions
**update**  |
[update:debug](update-debug.md) | Mostra les actualitzacions disponibles per l'aplicació
[update:execute](update-execute.md) | Executar una funció Update N en un mòdul, o executar-les totes
**user**  |
[user:debug](user-debug.md) | Mostrar els usuaris actuals de l'aplicació
[user:delete](user-delete.md) | Eliminar usuaris de l'aplicació
[user:login:clear:attempts](user-login-clear-attempts.md) | Esborrar intents de connexió d'un compte.
[user:login:url](user-login-url.md) | Retorna la 'one-time login url' d'un usuari.
[user:password:hash](user-password-hash.md) | Generar un 'hash' a partir d'una contrasenya de text sense format.
[user:password:reset](user-password-reset.md) | Reinicialitza una contrasenya per un usuari determinat.
**views**  |
[views:debug](views-debug.md) | Mostrar els recursos de vistes actuals de l'aplicació
[views:disable](views-disable.md) | Deshabilitar vistes
[views:enable](views-enable.md) | Habilitar vistes
**yaml**  |
[yaml:diff](yaml-diff.md) | Compara dos fitxers YAML amb l'objectiu de trobar diferències.
[yaml:merge](yaml-merge.md) | Combinar un o més fitxers YAML en un nou fitxer YAML. Es conserven els últims valors.
[yaml:split](yaml-split.md) | Dividir un fitxer YAML utilitzant una indentació com a criteri de separació
[yaml:update:key](yaml-update-key.md) | Reemplaçar una clau YAML en un fitxer YAML.
[yaml:update:value](yaml-update-value.md) | Actualitzar un valor per un clau determinada en un fitxer YAML.

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
--generate-doc | Mostrar les opcions i arguments dels comandaments com a "markdown"
--target | El nom del lloc web amb el qual vols interactuar (llocs locals o remots)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Continuar ometent la confirmació

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
