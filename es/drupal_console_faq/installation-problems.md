# Problemas de instalación

Cuando ejecuta Drupal Console desde su directorio raíz de Drupal 8, puede obtener distintos mensajes de error. A continuación se listan algunos problemas reportados y cómo resolverlos.

--- 

### Mensaje de error:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
Tiene que editar su valor 'host' en su archivo 'settings.php'. 

Navegue a `sites/default/settings.php`. En su archivo `settings.php` cambie el siguiente valor de `host`:
```
'host' => '127.0.0.1'
```
o si su archivo 'settings.php' ya existe:
```
'host' => '127.0.0.1'
```
cámbielo para que se lea:
```
'host' => 'localhost'. 
```
Después de hacer este cambio asegúrese de guardar el archivo. Luego pruebe ejecutar Drupal Console de nuevo.

---

### Mensaje de error:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
Cree un enlace simbólico apuntando a `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```


---

### Mensaje de error:
```
Fatal error: require(): Failed opening required 'drupal.php'
```
Esto puede ser causado por la extensión ionCube, que normalmente es usado para cifrar y descifrar ficheros PHP.
Esta extensión impide el normal funcionamiento de cualquier archivo phar que tenga llamadas require/include. 
Para solucionar el problema, deshabilite esta extensión.

---

### Mensaje de error:
```
The configuration date.timezone was missing and overwritten with America/Tijuana.
```
Su zona horaria no está configurada en el php.ini de su sistema, edite su archivo  php.ini 
Tenga en cuenta que para la línea de comandos existe otro php.ini diferente. 

Ejecute el comando `php --ini`y busque "Loaded Configuration File". Por ejemplo, en Ubuntu: 
```
Loaded Configuration File:         /etc/php5/cli/php.ini
```
Edite el archivo señalado y búsque la cadena: 
```
;date.timezone =
```
Descomente esta línea y asigne la zona horaria deseada como se explica en http://php.net/manual/en/timezones.php.
