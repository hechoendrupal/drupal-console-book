# Problemas de instalación

Cuando ejecuta Drupal Console desde su directorio raíz de Drupal 8, puede obtener distintos mensajes de error. A continuación se listan algunos problemas reportados y cómo resolverlos.

--- 

Mensaje de error:
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

Mensaje de error:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
Cree un enlace simbólico apuntando a `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

