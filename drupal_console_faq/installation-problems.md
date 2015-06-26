# Installation problems 

When you run DrupalConsole from your Drupal 8 root directory and you get this message:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
you will need to edit your 'host' in your 'settings.php' file. 

Navigate to 'sites/default/settings.php'. In your 'settings.php' file, change the 'host' to read:
```
'host' => '127.0.0.1'
```
or if your 'settings.php' file already reads:
```
'host' => '127.0.0.1'
```
change it to read:
```
'host' => 'localhost'. 
```
After you make the change, be sure to save the file and then run DrupalConsole again.
