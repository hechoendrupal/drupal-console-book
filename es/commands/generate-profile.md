# generate:profile
Genera un perfil.

**Uso:**
```
drupal generate:profile [options]
gpr
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--profile | Nombre del perfil
--machine-name | Nombre-máquina (sólo minúsculas y guiones bajos)
--description | Descripción del perfil
--core | Versión del core
--dependencies | Dependencias de módulos separadas por comas (p. ej. context, panels)
--themes | Nombre del tema
--distribution | Nombre de la distribución

## Ejemplos
* Generar un perfil especificando el nombre de perfil, el nombre máquina, una descripción, el core de Drupal y las dependencias de sus módulos
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
