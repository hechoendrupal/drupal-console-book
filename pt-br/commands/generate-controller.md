# generate:controller
Cria e Registra um controller

**Utilização:**
```
drupal generate:controller [options]
gcon
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do Controller
--routes | The routes, must be an array containing [title, method, path]
--services | Carrega serviços do container.
--test | Criar uma classe de teste

## Exemplos
* Generate controller specifying the module name, the class name and its routes
```
drupal generate:controller  \
  --module="modulename"  \
  --class="DefaultController"  \
  --routes='"title":"ControllerMethod", "name":"modulename.default_controller_hello", "method":"hello", "path":"/modulename/hello/{name}"'  \
  --test
```
