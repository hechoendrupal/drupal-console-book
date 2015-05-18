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
 config:debug  |   Shows the current configuration
 config:edit  |    Allows editing the selected configuration
 config:export  |  Exports current application configuration
 config:override  | Overrides config value in active configuration
**container**  |
 container:debug | Displays current services for an application
**generate**  |
 generate:authentication:provider  |   Generates an Authentication Provider
 [generate:command](generate_command.md)  |   Generate commands for the console
 [generate:controller](generate_controller.md)  | Generate & Register a controller
 generate:entity:config  | Generates a new "EntityConfig"
 generate:entity:content   | Generates a new "EntityContent"
 generate:form:config   |    Generates a new "ConfigFormBase"
 [generate:module](generate_module.md)  |    Generates a new module.
 [generate:permissions](generate_permissions.md)   |    Generate module permissions
 generate:plugin:block   |   Generates a plugin block
 generate:plugin:imageeffect  | Generates an image effect plugin
 generate:plugin:rest:resource  | Generates a REST resource plugin
 generate:plugin:rulesaction  | Generates a Rules action plugin
 [generate:service](generate_service.md)  | Generates a service
**migrate**  |
 migrate:debug  |  Display current migration available for the application
 migrate:execute  |  Execute a migration available for application
**module**  |
 module:debug  |   Displays current modules available for the application
 module:download  |   Downloads a module or modules in the application
 module:install  | Installs a module or modules in the application
 module:uninstall  |   Uninstalls a module or modules in the application
**rest**  |
 rest:debug  |     Display current REST resource(s) for the application
 rest:disable  |   Disables a REST resource for the application
 rest:enable  |    Enables a REST resource for the application
**router**  |
 router:debug  |   Displays current routes for the application
 router:rebuild  | Rebuilds routes for the application
**site**  |
 site:maintenance  |   Switches site into maintenance mode
 site:mode  |      Switches system performance configuration
 site:status  |    Displays current Drupal installation status
**test**  |
 test:debug  |     Lists unit tests available for the application
