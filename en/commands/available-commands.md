# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
**misc**  |
[about](about.md) | Displays basic information about Drupal Console project
[chain](chain.md) | Chain command execution
[check](check.md) | System requirement checker
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files.
[list](list.md) | Lists all available commands
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Rebuild and clear all site caches.
**config**  |
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Output configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Change a configuration object with a text editor.
[config:export](config-export.md) | Export current application configuration.
[config:export:content:type](config-export-content-type.md) | Export a specific content type and their fields.
[config:export:single](config-export-single.md) | Export a single configuration or a list of configurations as yml file(s).
[config:export:view](config-export-view.md) | Export a view in YAML format inside a provided module to reuse in other website.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import a single configuration or a list of configurations.
[config:override](config-override.md) | Override config value in active configuration.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:execute](cron-execute.md) | Execute cron implementations by module or execute all crons
[cron:release](cron-release.md) | Release cron system lock to run cron again
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Shows DB connection
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Dump structure and contents of a database
[database:log:clear](database-log-clear.md) | Remove events from DBLog table, filters are available
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restore structure and contents of a database.
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Displays breakpoints available in application
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | List configuration objects names and single configuration object.
[debug:config:settings](debug-config-settings.md) | Displays current key:value on settings file.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Displays current services for an application.
[debug:cron](debug-cron.md) | List of modules implementing a cron
[debug:database:log](debug-database-log.md) | Displays current log events for the application
[debug:database:table](debug-database-table.md) | Show all tables in a given database.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Displays current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Display current migration available for the application
[debug:module](debug-module.md) | Displays current modules available for application
[debug:multisite](debug-multisite.md) | List all multisites available in system
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Displays all plugin types.
[debug:queue](debug-queue.md) | Displays the queues of your application
[debug:rest](debug-rest.md) | Display current rest resource for the application
[debug:router](debug-router.md) | Displays current routes for the application or information for a particular route
[debug:settings](debug-settings.md) | List user Drupal Console settings.
[debug:site](debug-site.md) | List all known local and remote sites.
[debug:state](debug-state.md) | Show the current State keys.
[debug:test](debug-test.md) | List Test Units available for the application.
[debug:theme](debug-theme.md) | Displays current themes for the application
[debug:update](debug-update.md) | Displays current updates available for the application
[debug:user](debug-user.md) | Displays current users for the application
[debug:views](debug-views.md) | Displays current views resources for the application
[debug:views:plugins](debug-views-plugins.md) | Displays current views plugins for the application
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
[extend:global](extend-global.md) | Drupal Console global example
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "%s"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:module](generate-module.md) | Generate a module.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
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
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin
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
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions.
**project**  |
[project:new](project-new.md) | Create multisite new Drupal project
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**quick**  |
[quick:start](quick-start.md) | Download, install and serve a new Drupal project
**rest**  |
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Download a new Drupal project
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | View current Drupal Installation status
**state**  |
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Override a State key.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Run Test unit from tests available for application
**theme**  |
[theme:download](theme-download.md) | Download theme in application
[theme:install](theme-install.md) | Install theme or themes in the application
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Uninstall theme or themes in the application
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Execute a specific Update N function in a module, or execute all
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Delete users for the application
[user:login:clear:attempts](user-login-clear-attempts.md) | Clear failed login attempts for an account.
[user:login:url](user-login-url.md) | Returns a one-time user login url.
[user:password:hash](user-password-hash.md) | Generate a hash from a plaintext password.
[user:password:reset](user-password-reset.md) | Reset password for a specific user.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Disable a View
[views:enable](views-enable.md) | Enable a View

## Available options
Option | Details
-------|-------------
--help | Display this help message
--quiet | Suppress all output from the command
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output, and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | application.options.debug
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
