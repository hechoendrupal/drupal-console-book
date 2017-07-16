# How to copy configuration files
The first task you should do after installing Drupal Console is to execute the `init` command. Executing this command will copy the project configurations files to your local computer. Overriding values on these copied files is how you can change DrupalConsole behaviour.
 
```
drupal init [--override]
```

The first question you will be asked by the interactive mode of this command will be `Select destination to copy configuration:` and the options shown will vary depending the directory where you ran this command:  

Running this command outside of a drupal site directory the options will be.
```
 Select destination to copy configuration:
  [0] /etc/console/
  [1] /Users/username/.console/
 >
```

Running this command within a drupal site.
```
 Select destination to copy configuration:
  [0] /etc/console/
  [1] /Users/username/.console/
  [2] /path/to/drupal8.dev
 >
```

The rest of the options for this command are the same regardless of the directory you execute this command.
  