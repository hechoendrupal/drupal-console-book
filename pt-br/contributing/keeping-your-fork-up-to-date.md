# Mantendo seu fork atualizado
Depois de algum tempo, seu repositório bifurcado e o original (chamado upstream) acabará por sair da sincronização, deixando você com uma versão antiga e não suportada.

Para sincronizar as alterações que você faz em um fork com o repositório original, você deve:

## Configurar um fork remoto:
Especifique e configure um novo upstream remoto que aponte para o upstream no Git
```
git remote add upstream https://github.com/hechoendrupal/drupal-console.git
```
Para informações detalhadas, visite o guia do Github [Configurando um fork remoto](https://help.github.com/articles/configuring-a-remote-for-a-fork/)  

## Sincronizando o seu fork
Sincronize o seu fork para mantê-lo atualizado com o repositório upstream.
```
git fetch upstream
git merge upstream/master
```
Para informações detalhadas, visite o guia do Github [Sincronizando um fork](https://help.github.com/articles/syncing-a-fork/)
