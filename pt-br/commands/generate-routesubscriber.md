# generate:routesubscriber
Generate a RouteSubscriber

**Utilização:**
```
drupal generate:routesubscriber [options]
gr
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--name | Service name
--class | Class name

## Exemplos
* Generate a route subscriber specifying the module name, the route name and its class
```
drupal generate:routesubscriber  \
  --module="modulename"  \
  --name="modulename.route_subscriber"  \
  --class="RouteSubscriber"
```
