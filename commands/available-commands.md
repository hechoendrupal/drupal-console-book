# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
[chain](chain.md) | Chain command execution
[drush](drush.md) | Run drush from console.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Lists commands
[self-update](self-update.md) | Update the console to latest version.
**cache**  |
[cache:rebuild](cache-rebuild.md) | Rebuild and clear all site caches.
**config**  |
[config:debug](config-debug.md) | Show the current configuration.
[config:edit](config-edit.md) | Edit the selected configuration.
[config:export](config-export.md) | Export current application configuration.
[config:export:content:type](config-export-content-type.md) | Export a specific content type and their fields.
[config:export:single](config-export-single.md) | Export single configuration as yml file.
[config:import](config-import.md) | Import configuration to current application.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Override config value in active configuration.
**container**  |
[container:debug](container-debug.md) | Displays current services for an application.
**cron**  |
[cron:debug](cron-debug.md) | Display current views resources for the application
[cron:execute](cron-execute.md) | commands.views.execute.description
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generate an Authentication Provider
[generate:command](generate-command.md) | Generate commands for the console.
[generate:contenttype](generate-contenttype.md) | Generate a new content type (node / entity bundle)
[generate:controller](generate-controller.md) | Generate & Register a controller
[generate:doc](generate-doc.md) | commands.generate.doc.description
[generate:entity:config](generate-entity-config.md) | Generate a new "EntityConfig"
[generate:entity:content](generate-entity-content.md) | Generate a new "EntityContent"
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
[generate:service](generate-service.md) | Generate service
[generate:theme](generate-theme.md) | Generate a theme.
**migrate**  |
[migrate:debug](migrate-debug.md) | Display current migration available for the application
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:load](migrate-load.md) | Generate a migration entity.
**module**  |
[module:debug](module-debug.md) | Display current modules available for application
[module:download](module-download.md) | Install module or modules in the application
[module:install](module-install.md) | Install module or modules in the application
[module:uninstall](module-uninstall.md) | Install module or modules in the application
**rest**  |
[rest:debug](rest-debug.md) | Display current rest resource for the application
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:debug](router-debug.md) | Displays current routes for the application
[router:rebuild](router-rebuild.md) | Rebuild routes for the application
**site**  |
[site:maintenance](site-maintenance.md) | Switch site into maintenance mode
[site:mode](site-mode.md) | Switch system performance configuration
[site:new](site-new.md) | Create a new Drupal project
[site:status](site-status.md) | View current Drupal Installation status
**test**  |
[test:debug](test-debug.md) | List Test Units available for the application.
[test:run](test-run.md) | Run Test unit from tests available for application
**update**  |
[update:debug](update-debug.md) | Display current updates available for the application
[update:execute](update-execute.md) | Display current updates available for the application
**user**  |
[user:login:clear:attempts](user-login-clear-attempts.md) | Clear login failed attempts for an account.
[user:password:hash](user-password-hash.md) | Generate a hash from a plaintext password.
[user:password:reset](user-password-reset.md) | Reset password for a specific user.
**views**  |
[views:debug](views-debug.md) | Display current views resources for the application
[views:disable](views-disable.md) | Disable a View
[views:enable](views-enable.md) | Enable a View
**yaml**  |
[yaml:merge](yaml-merge.md) | Merge one or more YAML files in a new YAML file. Latest values are preserved.
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
--drupal | Path to Drupal root.
--shell | Launch the shell.
--env | The Environment name.
--no-debug | Switches off debug mode.
--learning | Generate a verbose code output.
--generate-chain | Print execution options and arguments as yaml output to be used in chain command
--generate-inline | Print execution options and arguments as inline call to be use in the future
--generate-doc | application.console.arguments.generate-doc

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
