# generate:theme
Generar un tema.

**Ús:**
```
drupal generate:theme [options]
gt
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--theme | Nom del tema
--machine-name | Nom màquina del tema (només minúscules i caràcter de subratllat)
--theme-path | Camí del tema
--description | Descripció del tema
--core | Versió del Core
--package | Paquet del tema
--global-library | Nom global de l'estil de la biblioteca
--libraries | Libraries
--base-theme | Base del tema (p.e. classy, stable)
--regions | Regions
--breakpoints | Punts d'interrupció (Breakpoints)

## Exemples
* Generate a theme without region and without breakpoint specifying the theme name, its machine name, the theme path, a description, the drupal core, the package name and the global library
```
drupal generate:theme  \
  --theme="AnotherTheme"  \
  --machine-name="anothertheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="PackageName"  \
  --global-library="global-styling"  \
  --base-theme="false"
```
* Generate a theme base on stable theme with two region defined and one breakpoint specifying the theme name, its machine name, the theme path, a description, the drupal core, the package name, a global library, its base, the regions and the breakpoint
```
drupal generate:theme  \
  --theme="MyTheme"  \
  --machine-name="mytheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="MyThemePackage"  \
  --global-library="global-styling"  \
  --base-theme="stable"  \
  --regions='"region_name":"Content", "region_machine_name":"content"'  \
  --regions='"region_name":"Panel", "region_machine_name":"panel"'  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
