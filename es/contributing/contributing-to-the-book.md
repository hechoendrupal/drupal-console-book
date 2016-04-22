
*Esta página es un punto de encuentro para traductores. Si usted lo es está invitado a editar esta página y dejar constancia de su opinión y trabajo.*

# Guía para traductores #
Si usted desea ayudar en la traducción de este libro sea bienvenido. Por favor tenga en cuenta las siguientes directrices:

* Se evita el trato de «tú» y se prefiere siempre de «usted». Además, preferimos frases impersonales antes que interpelar al lector, siempre que sea posible.
* «Introduzca» suena mal en hispanoamérica e «ingrese» suena mal en España. Por ello, preferimos utilizar «proporcione» o «escriba».
* Preferimos usar «archivo» en lugar de «fichero».


## Breve Glosario ##

* basepath - directorio raíz
* cache - caché
* computer - computadora
* Drupal Console - Drupal Console [no se traduce]
* debug - depurar
* entity - entidad
* environment - entorno
* merge - merge
* multisite - multisitio
* plugin - plugin
* requirement - requisito
* route - ruta
* service - servicio
* view - vista


# Generar traducidos todos los comandos disponibles #
*Con el paso del tiempo, los programadores de DrupalConsole van añadiendo cada vez más comandos, por lo que faltarán algunos comandos disponibles en este libro si no se van generando conforme se van añadiendo. Para solucionar este problema, con sólo un comando es posible generar (ya traducidos) todos los archivos .md pertenecientes a todos los comandos disponibles en un momento dado*

## Comando para generar la docuentación de todos los comandos disponibles actualmente ##
Suponiendo que tenga en su máquina local clonados los dos proyectos (DrupalConsole y este libro), debe ejecutar el siguiente comando desde un directorio donde esté Drupal instalado (o utilizando la opción *--root*):

``` drupal generate:doc:gitbook --path=/path/directorio/drupal-console-book/es ```

(Por favor, compruebe que tiene DrupalConsole configurado previamente en su máquina en español para obtener todos los comandos en dicho idioma. [Los archivos se generarán en el idioma en el que tenga DrupalConsole configurado.])

___
*Por favor, si tiene dudas, disiente o quiere hacer una propuesta, ponga un issue en este repositorio o edite directamente esta página.*
