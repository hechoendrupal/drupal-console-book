# Getting the project
You need to install two things to get DrupalConsole working:
1. The DrupalConsole Launcher
2. DrupalConsole itself

## Why do I need the Launcher?
This is a global executable that enables you to run the command, `drupal`, from any directory within your site's project. 
Without it you will be inconvenienced by having to run the command only from your drupal root directory. 

For example, if you have Drupal root in a /web directory, and a composer.json and your vendor directory in the directory above that, you will be able to run the `drupal` command from the same directory as the composer.json file. Even better, you can run it from any subdirectory under that as many levels deep as you would like to go.

[Install Drupal Console Launcher aka Global executable](./launcher.md)

## Install DrupalConsole in each one of your projects using Composer
Each one of your site projects should have it's own DrupalConsole installed. This is done using Composer.

[Install Drupal Console Using Composer](./composer.md) 

**Notes:**
* Starting on RC releases DrupalConsole must be installed per site. **Install Drupal Console using `composer global require` is no longer supported.**

* Starting with RC17 there are no longer any commands available that can be run outside of a drupal project. Commands are still available outside of your drupal root. 
For example, if your drupal root is in a /web subdirectory of your project the `drupal` command can still be run in the root of your project, where your composer.json file and vendor directory exist. 

**Help!**

See the FAQ section below (section 7) for help with specific installation and command issues.
