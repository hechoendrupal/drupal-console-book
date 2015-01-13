# Drupal Console

Some of you may have begun to explore Drupal 8 already, for those of you that have not had a chance yet I can tell you that there is a whole new new set of concepts. 

Drupal 8 is more advanced compared to its predecessor, writing a module involves a lot of boilerplate code, there is also a lot of things you need to know and do just to get started with building a new module and these can be repetitive and tedious therefore create opportunities for errors. 

Fortunately, a lot of that code can be generated automatically using a tool called the Drupal Console. 

Drupal Console is a project that takes the Symfony Console component and makes it available on Drupal to automatically generate most of the new Drupal 8 module requirements.

This tool does not only generated the module code, also helps you interact with your Drupal installation.

Drupal Console is another cool addition to the Proudly Found Elsewhere school of thought as it leverages the Symfony Console component to handle the CLI part.

The purpose of this project is to leverage the Symfony Console Component to provide a CLI tool to automate the creation of drupal 8 modules and other recurring tasks.

As described on the Symfony documentation
>The Console component eases the creation of beautiful and testable command line interfaces.
The Console component allows you to create command-line commands. Your console commands can be used for any recurring task, such as cronjobs, imports, or other batch jobs.  

http://symfony.com/doc/current/components/console/introduction.html

#### Project Goals:
* Take advantage of Symfony Console Component to generate command.
* Take advantage of Twig Component in order to render PHP, YML and other files.
* Take advantage of OOP and modern development practices.
* No plans to support previous versions of Drupal.

#### What is out of the box?
* Generators:
 * Generates module and info files.
 * Generates PSR-4 compliant directory structure for a module.
 * Register routes on YML files and map to controller and form PHP Classes.
 * Create classes adding namespaces, uses and also the extend and implements keywords when required.
 * Support adding services using Dependency Injection on class generation.

* Other commands:
 * List registered services on the service container
 * List registered routes on the routing system
 * Rebuilt routes

#### Who will benefit of using it?
* **Module Maintainers & Developers**  
  Create & Migrate contributed modules to Drupal 8.

* **Drupal Trainers & Consultors**  
  Train developers on Drupal 8.

* **Drupal Shops**  
  Reduce module development time for Drupal 8.
