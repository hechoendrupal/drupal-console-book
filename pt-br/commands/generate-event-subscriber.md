# generate:event:subscriber
Gerar um assinante do evento

**Utilização:**
```
drupal generate:event:subscriber [options]
ges
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--name | Service name
--class | Class name
--events | Carrega eventos do container
--services | Carrega serviços do container.

## Exemplos
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
