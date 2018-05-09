# generate:profile
Génère un profil.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | Le nom du profil
--machine-name | Le nom machine (uniquement minuscules ou underscore)
--profile-path | The path of the profile
--description | Description du profil
--core | Version du core
--dependencies | Dépendances du module séparées par des virgules (i.e. context, panels)
--themes | the theme name
--distribution | Le nom de la distribution

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
