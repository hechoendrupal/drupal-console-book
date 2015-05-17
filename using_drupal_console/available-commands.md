# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
drush | Runs Drush from Drupal Console
help | Displays help for a Drupal Console command
list | Lists Drupal Console commands
self-update | Updates Drupal Console to latest version
**cache**  |
cache:rebuild  | Rebuilds and clears all site caches
**config**  |
 config:debug  |   Show the current configuration.
 config:edit  |    Edit the selected configuration.
 config:export  |  Export current application configuration.
 config:override  |    Override config value in active configuration.
**container**  |
 container:debug | Displays current services for an application.
**generate**  |
 generate:authentication:provider  |   Generate an Authentication Provider
 generate:command  |   Generate commands for the console.
 generate:controller  | Generate & Register a controller
 generate:entity:config  | Generate a new "EntityConfig"
 generate:entity:content   | Generate a new "EntityContent"
 generate:form:config   |    Generate a new "ConfigFormBase"
 [generate:module](generate_module.md)  |    Generate a module.
 generate:permissions   |    Generate module permissions
 generate:plugin:block   |   Generate a plugin block
 generate:plugin:imageeffect  | Generate image effect plugin.
 generate:plugin:rest:resource  | Generate plugin rest resource
 generate:plugin:rulesaction  | Generate a plugin rule action
 generate:service  | Generate service
**migrate**  |
 migrate:debug  |  Display current migration available for the application
 migrate:execute  |    Execute a migration available for application
**module**  |
 module:debug  |   Display current modules available for application
 module:download  |   Install module or modules in the application
 module:install  | Install module or modules in the application
 module:uninstall  |   Install module or modules in the application
**rest**  |
 rest:debug  |     Display current rest resource for the application
 rest:disable  |   Disable a rest resource for the application
 rest:enable  |    Enable a rest resource for the application
**router**  |
 router:debug  |   Displays current routes for the application
 router:rebuild  | Rebuild routes for the application
**site**  |
 site:maintenance  |   Switch site into maintenance mode
 site:mode  |      Switch system performance configuration
 site:status  |    View current Drupal Installation status
**test**  |
 test:debug  |     List Test Units available for the application.
