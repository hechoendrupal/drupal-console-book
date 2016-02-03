# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
[about](about.md) | Display basic information about Drupal Console project
[chain](chain.md) | Chain command execution
[help](help.md) | Displays help for a command
[settings:init](settings-init.md) | Copy configuration files to user home directory.
[list](list.md) | Lists all available commands
[server](server.md) | Runs PHP built-in web server
**cache**  |
[cache:rebuild](cache-rebuild.md) | Rebuild and clear all site caches.
**config**  |
[config:debug](config-debug.md) | Show the current configuration.
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Edit the selected configuration.
[config:export](config-export.md) | Export current application configuration.
[config:export:content:type](config-export-content-type.md) | Export a specific content type and their fields.
[config:export:single](config-export-single.md) | Export single configuration as yml file.
[config:export:view](config-export-view.md) | Export a view in YAML format inside a provided module to reuse in other website.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Override config value in active configuration.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Displays current services for an application.
**create**  |
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | List of modules implementing a cron
[cron:execute](cron-execute.md) | Execute cron implementations by module or execute all crons
[cron:release](cron-release.md) | Release cron system lock to run cron again
**database**  |
[database:client](database-client.md) | Launch a DB client if it's available
[database:connect](database-connect.md) | Shows DB connection
[database:dump](database-dump.md) | Dump structure and contents of a database
[database:log:clear](database-log-clear.md) | Remove events from DBLog table, filters are available
[database:log:debug](database-log-debug.md) | Display current log events for the application
[database:restore](database-restore.md) | Restore structure and contents of a database.
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
[database:table:drop](database-table-drop.md) | Drop all tables in a given database.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:command](generate-command.md) | Generate commands for the console.
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc:dash](generate-doc-dash.md) | Generate the DrupalConsole.docset package for Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Generate documentations for Commands
[generate:entity:bundle](generate-entity-bundle.md) | Generate a new content type (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Generate a new config entity
[generate:entity:content](generate-entity-content.md) | Generate a new content entity
[generate:event:subscriber](generate-event-subscriber.md) | Generate an event subscriber
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Generate an implementation of hook_form_alter() or hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:module](generate-module.md) | Generate a module.
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Generate a plugin block
[generate:plugin:condition](generate-plugin-condition.md) | Generate a plugin condition.
[generate:plugin:field](generate-plugin-field.md) | Generate field type, widget and formatter plugins.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Generate field formatter plugin.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Generate field type plugin.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Generate image effect plugin.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | Delete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Display current migration available for the application
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:debug](module-debug.md) | Display current modules available for application
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | List all multisites available in system
**rest**  |
[rest:debug](rest-debug.md) | Display current rest resource for the application
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:debug](router-debug.md) | Displays current routes for the application
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:init](settings-init.md) | Copy configuration files to user home directory.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | List all known local and remote sites.
[site:install](site-install.md) | Install a Drupal project
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Create a new Drupal project
[site:statistics](site-statistics.md) | Show the current statistics of website.
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
[user:login:clear:attempts](user-login-clear-attempts.md) | Clear failed login attempts for an account.
[user:login:url](user-login-url.md) | Returns a one-time user login url.
[user:password:hash](user-password-hash.md) | Generate a hash from a plaintext password.
[user:password:reset](user-password-reset.md) | Reset password for a specific user.
**views**  |
[views:debug](views-debug.md) | Display current views resources for the application
[views:disable](views-disable.md) | Disable a View
[views:enable](views-enable.md) | Enable a View
**yaml**  |
[yaml:diff](yaml-diff.md) | Compare two YAML files in order to find differences between them.
[yaml:merge](yaml-merge.md) | Merge two or more YAML files in a new YAML file. Latest values are preserved.
[yaml:split](yaml-split.md) | Split a YAML file using indent as separator criteria
[yaml:update:key](yaml-update-key.md) | Replace a YAML key in a YAML file.
[yaml:update:value](yaml-update-value.md) | Update a value for a specific key in a YAML file.

## Available options
Option | Details
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--no-debug | Switches off debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multisite environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
