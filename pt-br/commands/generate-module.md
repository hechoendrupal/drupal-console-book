# generate:module
Criar um módulo.

**Utilização:**
```
drupal generate:module [options]
gm
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo
--machine-name | O nome de máquina (apenas minúsculas e sublinhado)
--module-path | O caminho do módulo
--description | Descrição do módulo
--core | Versão do core
--package | Pacote do módulo
--module-file | Add a .module file
--features-bundle | Define module as feature using the given Features bundle name
--composer | Adicionar um arquivo composer.json
--dependencies | Dependências do módulo separados por vírgulas (i.e. context, panels)
--test | Criar uma classe de teste
--twigtemplate | Generate theme template

## Exemplos
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
