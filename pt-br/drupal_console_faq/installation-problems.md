# Problemas de instalação 

Quando você executa o DrupalConsole do diretório raiz do Drupal 8, você pode obter mensagens de erro diferentes, tentaremos compilar os problemas relatados e como corrigi-los

--- 

Mensagem de erro:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
Você precisará editar a diretiva 'host' em seu arquivo 'settings.php'. 

Navegue até `sites/default/settings.php`. No seu arquivo `settings.php` , mude a diretiva `host` para ler:
```
'host' => '127.0.0.1'
```
ou se o seu 'settings.php' já lê:
```
'host' => '127.0.0.1'
```
altere-o para ler:
```
'host' => 'localhost'. 
```
Após realizar a alteração, certifique-se de salvar o arquivo e então executar o Drupal Console.

---

Mensagem de erro:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
Criando um link simbólico apontando para `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

