# generate:profile
Genera un perfil.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | Nombre del perfil
--machine-name | Nombre-máquina (sólo minúsculas y guiones bajos)
--description | Descripción del perfil
--core | Versión del core
--dependencies | Dependencias de módulos separadas por comas (p. ej. context, panels)
--themes | commands.generate.profile.options.themes
--distribution | Nombre de la distribución

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
