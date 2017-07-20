# Getting the project

The Drupal Console is a modular project using multiple repositories.

Main repositories:
* [drupal/console](https://github.com/hechoendrupal/drupal-console)
* [drupal/console-core](https://github.com/hechoendrupal/drupal-console-core)
* [drupal/console-extend-plugin](https://github.com/hechoendrupal/drupal-console-extend-plugin)
* [drupal-console-dotenv](https://github.com/weknowinc/drupal-console-dotenv)

Additional projects:
* [drupal/console-develop](https://github.com/weknowinc/drupal-console-develop)
* [drupal-console-yaml](https://github.com/weknowinc/drupal-console-yaml)
        
Languages are also managed into separated repositories:
* [drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
* [drupal-console-es](https://github.com/hechoendrupal/drupal-console-es)

## Fork
You should fork the repositories that you want to contribute. For this task you can use the github GUI.

## Clone
You need to define a directory where you will clone the repositories. i.e. `/Users/username/drupal-console-code`
```
cd /Users/username/drupal-console-code
git clone git@github.com:[your-github-user-here]/drupal-console.git
git clone git@github.com:[your-github-user-here]/drupal-console-core.git
git clone git@github.com:[your-github-user-here]/drupal-console-en.git
```

## Install dependencies
Now that you have cloned the repositories, you need to download dependencies using Composer.
```
cd /Users/username/drupal-console-code/[cloned-repository]
composer install
```

Read the next step to learn how to link and test these repositories into a Drupal site.
