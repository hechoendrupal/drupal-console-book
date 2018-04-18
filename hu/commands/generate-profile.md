# generate:profile
Profil létrehozása.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | A profil neve
--machine-name | A programok által használt név (csak kisbetűk és aláhúzás)
--profile-path | The path of the profile
--description | Profil leírása
--core | Drupal alaprendszer verziója
--dependencies | Modulfüggőségek vesszővel elválasztva (pl. context, panels)
--themes | the theme name
--distribution | A disztribúció neve

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
