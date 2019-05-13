# Commandes disponibles pour de Drupal Console

**Note:** Les commandes Drupal Console commands *doivent* être exécutées depuis la racine de l'installation de Drupal.

Commande Drupal Console | Détails
------------ | -------------
**misc**  |
[about](about.md) | Affiche les informations concernant le projet Drupal Console
[chain](chain.md) | Séquence d'exécution de commandes
[check](check.md) | Vérificateur de configuration minimale système
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Exécute une commande externe.
[help](help.md) | Affiche de l'aide pour une commande
[init](init.md) | Copie les fichiers de configuration dans le répertoire dédié de l'utilisateur.
[list](list.md) | Liste les commandes
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Lance le serveur web PHP interne
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruit l'ensemble des caches du site.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Supprimer la configuration
[config:diff](config-diff.md) | Affiche les items de configuration qui sont différents dans la configuration active par rapport à un dossier.
[config:edit](config-edit.md) | Éditer la configuration sélectionnée.
[config:export](config-export.md) | Exporte la configuration actuelle de l'application.
[config:export:content:type](config-export-content-type.md) | Exporte un type de contenu avec les champs qui le composent.
[config:export:single](config-export-single.md) | Exporte une unique configuration sous la forme d'un fichier YAML.
[config:export:view](config-export-view.md) | Exporte une vue vue dans le format YAML au sein d'un module pour la réutiliser sur un autre site.
[config:import](config-import.md) | Importe une configuration dans le site courant.
[config:import:single](config-import-single.md) | Importer la configuration sélectionnée.
[config:override](config-override.md) | Surcharge la valeur d'une configuration dans la configuration active.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Créé des commentaires factices pour votre application Drupal 8.
[create:nodes](create-nodes.md) | Créer des nœuds factices pour votre application Drupal 8.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Génère des termes de taxonomie factices pour votre application Drupal 8.
[create:users](create-users.md) | Génère des utilisateurs factices pour votre application Drupal 8.
[create:vocabularies](create-vocabularies.md) | Génère des vocabulaires factices pour votre application Drupal
**cron**  |
[cron:execute](cron-execute.md) | Lancer une tâche cron d'un module particulier ou l'ensembles des tâches
[cron:release](cron-release.md) | Relâche le verrou lié au cron afin de pouvoir le relancer
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Lancer une base de données client si disponible
[database:connect](database-connect.md) | Lancer une base de donnée client si disponible
[database:drop](database-drop.md) | Supprime toutes les tables d'une base de données.
[database:dump](database-dump.md) | Exporte la structure et le contenu de votre base de données MySQL
[database:log:clear](database-log-clear.md) | Vide la table DBLog contenant les événements, avec possibilité de fitrer
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restaure la structure et le contenu de votre base de données MySQL depuis une sauvegarde
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Affiche les breakpoints disponibles dans l'application
[debug:cache:context](debug-cache-context.md) | Affiche le contexte de cache courant pour l'application.
[debug:chain](debug-chain.md) | Liste des fichiers chain disponibles
[debug:config](debug-config.md) | Affiche la configuration actuelle.
[debug:config:settings](debug-config-settings.md) | Affiche la paire key:value du fichier de configuration.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Affiche les services actuels d'une application.
[debug:cron](debug-cron.md) | Liste des modules implémentant une tâche cron
[debug:database:log](debug-database-log.md) | Affiche les entrées courantes du journal pour l'application
[debug:database:table](debug-database-table.md) | Montre toutes les tables d'une base de données spécifique.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Affiche les événements disponibles
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | Liste des styles d'images sur le site
[debug:libraries](debug-libraries.md) | Affiche les librairies disponibles dans l'application
[debug:migrate](debug-migrate.md) | Affiche la migration actuellement disponible dans l'application
[debug:module](debug-module.md) | Affiche les modules actuellement disponibles dans l'application
[debug:multisite](debug-multisite.md) | Liste toutes les installations multi-sites disponibles dans le système
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Affiche tous les types de plugins, les instances de plugin d'un certain type, ou la définition d'un plugin spécifique.
[debug:queue](debug-queue.md) | Affiche la queue de votre application
[debug:rest](debug-rest.md) | Affiche la resource Rest disponible dans l'application
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Affiche les routes de l'application
[debug:settings](debug-settings.md) | Affiche la configuration personnalisée de Drupal Console.
[debug:site](debug-site.md) | Liste tous les sites connus en local et distants.
[debug:state](debug-state.md) | Affiche les clés de l'Etat actuel.
[debug:test](debug-test.md) | Liste les tests unitaires disponibles dans l'application.
[debug:theme](debug-theme.md) | Affiche les thèmes actuels de l'application
[debug:theme:keys](debug-theme-keys.md) | Affiche toutes les clefs de thème définies par les fonctions hook_theme
[debug:update](debug-update.md) | Affiche les mises à jour actuellement disponibles pour l'application
[debug:user](debug-user.md) | Liste les utilisateurs de l'application
[debug:views](debug-views.md) | Affiche des informations à propos des vues de l'application
[debug:views:plugins](debug-views-plugins.md) | Affiche les plugins de vues de l'application
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Supprime une entité spécifique
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | Affiche des informations concernant des champs.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | Générer un système d'authentification
[generate:breakpoint](generate-breakpoint.md) | Générer un breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Génère une commande utilisable via la console
[generate:controller](generate-controller.md) | Générer & enregistrer un contrôleur
[generate:entity:bundle](generate-entity-bundle.md) | Génère un nouveau type de contenu (nœud / bundle d'entité)
[generate:entity:config](generate-entity-config.md) | Génère une nouvelle entité de configuration
[generate:entity:content](generate-entity-content.md) | Génère une nouvelle entité de contenu
[generate:event:subscriber](generate-event-subscriber.md) | Génère un abonné à un événement
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Génère une implémentation de hook_form_alter() ou de hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Génère une implémentation de hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Génère un module.
[generate:module:file](generate-module-file.md) | Génère un  fichier .module
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Génère un plugin de bloc
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Génère un plugin de bouton CKEditor.
[generate:plugin:condition](generate-plugin-condition.md) | Génère un plugin de condition.
[generate:plugin:field](generate-plugin-field.md) | Génère des plugins de type, de widget et de formateur de champ.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Générer un plugin de formateur de champ.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Génère un plugin de type de champ.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Génère un plugin de widget de champ.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Génère un plugin d'effet d'image
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Génère un plugin de formateur d'image.
[generate:plugin:mail](generate-plugin-mail.md) | Génère un plugin de courriel
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Génère un plugin de ressource rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Génère un plugin d'action de rule
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Génère une implémentation d'un squelette de plugin pour les plugins Drupal Console qui n'ont pas de générateur spécifique
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Génère un type de plugin avec des annotations (mécanisme de découverte)
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Génère un plugin personnalisé de champ de vue.
[generate:post:update](generate-post-update.md) | Génère une implémentation de hook_post_update_NAME()
[generate:profile](generate-profile.md) | Génère un profil.
[generate:routesubscriber](generate-routesubscriber.md) | Génèrer un RouteSubscriber
[generate:service](generate-service.md) | Génère un service
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Génère un theme.
[generate:twig:extension](generate-twig-extension.md) | Génère une extension Twig.
[generate:update](generate-update.md) | Génère une implémentation de hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Vide les caches par style d'image ou pour tous les styles d'image
**locale**  |
[locale:language:add](locale-language-add.md) | Ajoute une langue à votre site
[locale:language:delete](locale-language-delete.md) | Supprime une langue de votre site
[locale:translation:status](locale-translation-status.md) | Liste des mises à jour de traduction disponibles
**migrate**  |
[migrate:execute](migrate-execute.md) | Exécute une migration disponible dans l'application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Charge et créé les migrations adéquates pour la base de données existante indiquée
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Télécharge le module ou les modules dans l'application
[module:install](module-install.md) | Installe un ou plusieurs modules dans l'application
[module:path](module-path.md) | Renvoie le chemin relatif vers le module (ou le chemin absolu)
[module:uninstall](module-uninstall.md) | Désinstalle le ou les modules de l'application
[module:update](module-update.md) | Met à jour le cœur, ou bien un ou plusieurs modules de l'application
**multisite**  |
[multisite:new](multisite-new.md) | Prépare les fichiers pour une nouvelle installation multi-sites.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Reconstruit les permissions d'accès aux noeuds. Le processus supprimera tous les privilèges sur le contenu et les remplacera par des permissions basés sur les modules et la configuration actuels.
**queue**  |
[queue:run](queue-run.md) | Traite la queue sélectionnée.
**rest**  |
[rest:disable](rest-disable.md) | Désactive une ressource Rest dans l'application
[rest:enable](rest-enable.md) | Active une ressource Rest de l'application
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Reconstruit les routes de l'application
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change une valeur de configuration spécifique dans le fichier de configuration de Drupal Console
**site**  |
[site:import:local](site-import-local.md) | Importe/Configure un projet local Drupal existant
[site:install](site-install.md) | Installe un site Drupal
[site:maintenance](site-maintenance.md) | Fait basculer le site en mode maintenance
[site:mode](site-mode.md) | Change la configuration de la performance du système
[site:statistics](site-statistics.md) | Affiche les statistiques actuelles du site web.
[site:status](site-status.md) | Voir l'état actuel de l'installation Drupal
**state**  |
[state:delete](state-delete.md) | Supprime l'Etat
[state:override](state-override.md) | Surcharge la clé d'un Etat.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Lance un test unitaire à partir des tests mis à disposition par l'application
**theme**  |
[theme:download](theme-download.md) | Télécharge un thème dans l'application
[theme:install](theme-install.md) | Installe un ou plusieurs thèmes dans l'application
[theme:path](theme-path.md) | Renvoie le chemin relatif du thème (ou le chemin absolu)
[theme:uninstall](theme-uninstall.md) | Désisntalle un ou plusieurs thèmes dans l'application
**update**  |
[update:entities](update-entities.md) | Applique des mises à jour d'entités
[update:execute](update-execute.md) | Exécute une fonction de mise à jour N dans un module, ou bien exécute toutes les fonctions
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Supprime des utilisateurs de l'application
[user:login:clear:attempts](user-login-clear-attempts.md) | Nettoie les tentatives de connexion ratés pour un compte.
[user:login:url](user-login-url.md) | Retourne une url de connection à validité unique pour un utilisateur.
[user:password:hash](user-password-hash.md) | Génère un hash à partir d'un mot de passe en texte brut.
[user:password:reset](user-password-reset.md) | Réinitialise le mot de passe pour un utilisateur spécifique.
[user:role](user-role.md) | Ajoute/retire un rôle à un utilisateur donné
**views**  |
[views:disable](views-disable.md) | Désactive une vue
[views:enable](views-enable.md) | Active une vue

## Available options
Option | Details
-------|-------------
--help | Afficher ce message d'aide
--quiet | Ne renvoyer aucun message
--verbose | Augmenter la verbosité des messages : 1 pour une sortie normale, 2 pour une sortie plus verbeuse et 3 pour débugger
--version | <info>"%s"</info> version <comment>"%s"</comment>
--ansi | Forcer une sortie ANSI
--no-ansi | Désactiver la sortie ANSI
--no-interaction | Ne poser aucune question interactive
--env | Nom de l'environnement.
--root | Définir la racine de l'instance de drupal à utiliser
--debug | Switches on debug mode
--learning | Affiche plus d'informations.
--generate-chain | Affiche les commandes ainsi que leurs paramètres sous le format yaml pour être réutilisé dans une commande chaînée
--generate-inline | Affiche les commandes ainsi que leurs paramètres sur une ligne pour une réutilisation future
--generate-doc | Affiche les options et paramètres de la commande sous le format markdown
--target | Nom du site avec lequel vous voulez interagir (Pour les sites locaux ou distants)
--uri | Définir l'URI du site Drupal à utiliser (dans le cas d'un environnement multisite ou lors de l'usage d'un port non standard)
--yes | Passe la confirmation et lance le processus

## Arguments disponibles
Argument | Détails
---------|-------------
command | La commande à exécuter
