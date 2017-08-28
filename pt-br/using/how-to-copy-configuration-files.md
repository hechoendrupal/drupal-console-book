# Como copiar arquivos de configuração
A primeira tarefa que você deve fazer após a instalação do Drupal Console é executar o comando `init`. Executar este comando copiará os arquivos de configurações do projeto para o diretório `~ / .console /`. A substituição de valores nesses arquivos copiados é como você pode alterar o comportamento do DrupalConsole.
 
 ```
 $ drupal init [--override]
 ```
 
### Quais arquivos são copiados ao executar o comando `init`.
```
 ~/.console/ 
 ├── aliases.yml 
 ├── chain
 │   ├── quick-start.yml
 │   └── sample.yml 
 ├── config.yml 
 ├── console.rc 
 ├── drupal.fish 
 └── sites 
     └── sample.yml 
```