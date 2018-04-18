# generate:profile
Generar un perfil.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | Nom del perfil
--machine-name | Nom màquina del perfil (només minúscules)
--profile-path | The path of the profile
--description | Descripció del perfil
--core | Versió del Core
--dependencies | Dependències del mòdul separades per comes (p.e. context, panels)
--themes | the theme name
--distribution | Nom de la distribució

## Examples
* Generate a profile specifying the profile name, the machine name, a description, the core and its module dependencies
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
