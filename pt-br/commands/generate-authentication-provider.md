# generate:authentication:provider
Gerar um provedor de autenticação

**Utilização:**
```
drupal generate:authentication:provider [options]
gap
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Classe do provedor de autenticação
--provider-id | ID do Provedor

## Exemplos
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
