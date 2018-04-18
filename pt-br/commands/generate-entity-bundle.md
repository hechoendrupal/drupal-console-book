# generate:entity:bundle
Gera um novo tipo de conteúdo (node / entity bundle)

**Utilização:**
```
drupal generate:entity:bundle [options]
geb
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--bundle-name | O tipo de conteúdo's nome de máquina
--bundle-title | O nome amigável do tipo de conteúdo

## Exemplos
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
