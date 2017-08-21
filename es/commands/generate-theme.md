# generate:theme
Genera un tema.

**Uso:**
```
drupal generate:theme [options]
gt
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--theme | commands.generate.theme.options.module
--machine-name | Nombre máquina (sólo minúsculas y guión bajo)
--theme-path | commands.generate.theme.options.module-path
--description | Descripción del tema
--core | Versión del core
--package | Paquete del tema
--global-library | Nombre de la librería de estilo global
--libraries | Librerías
--base-theme | Tema base (por ejemplo: classy, stable)
--regions | Regiones
--breakpoints | Puntos de ruptura

## Ejemplos
* Generar un tema sin regiones y sin breakpoints especificando el nombre del tema, su nombre máquina, la ruta del tema, una descripción, el core de Drupal, el nombre del paquete y la librería global
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
* Generar un tema base sobre un tema estable con dos regiones definida y un breakpoint especificando el nombre, su nombre máquina, la ruta del theme, una descripción, el core de drupal, el nombre del paquete, una librería global, el tema base, 
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
