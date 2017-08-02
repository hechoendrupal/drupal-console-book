
*This page is a meeting point for translators. If you're one, consider yourself invited to edit this page and state constancy of your opinions and your work*

# Guide for translators #
If you would like to help in the translation of this book, consider yourself welcome. Please, keep in mind the following guidelines:

* Be gender neutral.
* Code and examples should not be translated.
* Use a formal style. We prefer a formal tone.

# Generar traducidos todos los comandos disponibles #
*Over time, DrupalConsole programmers add more and more commands, so it's possible some available commands weren't present in this book if they are not added to the book as they are added.
In order to solve this problem, with a single command is possible to generate (already translated) all the .md files belonging to all the available commands*

##Comand for generating documentation of all available commands currently##
If you have cloned in your local machine both projects, DrupalConsole and this book, you should execute the following command from a directory where Drupal were installed (or using the *--root* option):

``` drupal generate:doc:gitbook --path=/path/directorio/drupal-console-book/en ```

(Please, check you have DrupalConsole correctly configured previously in your local machine in your desired language in order to get all the commands in your language.
[Files will be generated in the language you have DrupalConsole configured])

___
*Please, in case of doubt, dissent or just if you want to make a proposal, please file an issue on this repository or edit directly this page.*
