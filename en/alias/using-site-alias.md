# Using site alias

Drupal Console allows you to run commands from your local server but actually execute them on a local, remote or virtual (VM, Docker) Drupal installation by using site aliases.

Site alias files uses YAML format to provide a collection of predefined options once an alias is defined you can call them using a short name. 

A site alias could be defined for a remote site by site using `type: ssh`. In this case the ssh command will be used to execute the command on the remote installation.   

Site alias files are discoverable from the following paths:

* **Globally**: `~/.console/sites/`
* **Per site**: `/path/to/site/console/sites/`

## Site alias valid options

List of valid key/value options for site alias file configuration.
 
* **root**: Drupal root project directory.
* **host**: Domain name of the remote system. Not required on local sites.
* **port**: The port to use when connecting via ssh. The port 22 used by default. 
* **user**: The username to use when connecting via ssh.
* **options**: Array of valid DrupalConsole options.
* **arguments**: Array of valid DrupalConsole arguments.
* **extra-options**: Used only when the target requires extra options, such as alternative authentication method and/or alternative identity file. 
* **type**: Type of site to interact with. Allowed options `local`, `ssh`, `container`. The `local` option is used by default.

**NOTE:**: The values `root` and `type` are required.
