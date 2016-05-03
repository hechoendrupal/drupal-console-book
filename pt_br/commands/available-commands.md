# Comandos Drupal Console disponíveis

**Nota:** Comandos Drupal Console que *devem* ser executados desde a raiz de uma instalação Drupal 8.

Comando Drupal Console | Detalhes
------------ | -------------
[about](about.md) | Exibir informações básicas sobre projeto Drupal Console
[chain](chain.md) | Execução de comandos em sequência
[check](check.md) | commands.check.description
[help](help.md) | Displays help for a command
[init](init.md) | commands.init.description
[list](list.md) | Lists commands22
[self-update](self-update.md) | Update the console to latest version.
[server](server.md) | Executar o servidor PHP atual
**breakpoints**  |
[breakpoints:debug](breakpoints-debug.md) | commands.breakpoints.debug.description
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruir e limpar todos os caches do site.
**chain**  |
[chain:debug](chain-debug.md) | List available chain files.
**config**  |
[config:debug](config-debug.md) | Exibe a configuração atual.
[config:delete](config-delete.md) | Delete configuration
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Edit the selected configuration.
[config:export](config-export.md) | Exportar a configuração atual da aplicação.
[config:export:content:type](config-export-content-type.md) | Exportar um content-type específico e todos os seus fields.
[config:export:single](config-export-single.md) | Exportar uma configuração única como um arquivo YML.
[config:export:view](config-export-view.md) | Exportar uma view no formato YAML em um módulo, para reutilizar em outro website.
[config:import](config-import.md) | Importar configuração do estado atual da aplicação.
[config:import:single](config-import-single.md) | Import the selected configuration.
[config:override](config-override.md) | Sobrescrever valor de configuração ativa.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Exibe serviços atuais para um aplicativo.
**create**  |
[create:comments](create-comments.md) | Create dummy comments for your Drupal 8 application.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:debug](cron-debug.md) | Lista de módulos quem implementam uma chamada no cron
[cron:execute](cron-execute.md) | Executar cron de um módulo específico ou todos para executar todas as implementações
[cron:release](cron-release.md) | Desbloquear cron para voltar a executar
**database**  |
[database:client](database-client.md) | Iniciar um cliente de banco de dados se ele está disponível
[database:connect](database-connect.md) | Iniciar um cliente de banco de dados se ele está disponível
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Dump da estrutura e conteúdos da base de dados e tabelas MySQL
[database:log:clear](database-log-clear.md) | Remove eventos da tabela DBLog, filtros disponíveis
[database:log:debug](database-log-debug.md) | Exibir eventos de log atuais do aplicativo
[database:restore](database-restore.md) | Restaurar a estrutura e conteúdo das bases de dados e tabelas do MySQL
[database:table:debug](database-table-debug.md) | Show all tables in a given database.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Gerar um provedor de autenticação
[generate:command](generate-command.md) | Cria comandos via console.
[generate:controller](generate-controller.md) | Cria e Registra um controller
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | Generate a printable cheatsheet for Commands
[generate:doc:dash](generate-doc-dash.md) | Gerar o pacote DrupalConsole.docset para Dash
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | Gerar documentação para os comandos
[generate:entity:bundle](generate-entity-bundle.md) | Gera um novo tipo de conteúdo (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Gerar uma nova entidade de configuração
[generate:entity:content](generate-entity-content.md) | Gerar uma nova entidade de conteúdo
[generate:event:subscriber](generate-event-subscriber.md) | Gerar um assinante do evento
[generate:form](generate-form.md) | Cria um novo "FormBase"
[generate:form:alter](generate-form-alter.md) | Gera uma implementação de hook_form_alter() ou hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Cria um novo "ConfigFormBase"
[generate:module](generate-module.md) | Criar um módulo.
[generate:permissions](generate-permissions.md) | Gerar permissões ao módulo
[generate:plugin:block](generate-plugin-block.md) | Criar plugin de bloco.
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Generate CKEditor button plugin.
[generate:plugin:condition](generate-plugin-condition.md) | Criar um plugin de condition.
[generate:plugin:field](generate-plugin-field.md) | Gera plugins de widgets, fortmato e tipo de campo
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Gerar um plugin de formato de campo.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Gerar um plugin de tipo de campo
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Criar plugin de efeito de imagem.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Criar serviço
[generate:theme](generate-theme.md) | Generate a theme.
**image**  |
[image:styles:debug](image-styles-debug.md) | List image styles on the site
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**libraries**  |
[libraries:debug](libraries-debug.md) | commands.libraries.debug.description
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | DElete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:debug](migrate-debug.md) | Display current migration available for the application
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:debug](module-debug.md) | Display current modules available for application
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Install module or modules in the application
[module:uninstall](module-uninstall.md) | Uninstall module or modules in the application
**multisite**  |
[multisite:debug](multisite-debug.md) | List all multisites available in system
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Rebuild node access permissions. Rebuilding will remove all privileges to content and replace them with permissions based on the current modules and settings.
**plugin**  |
[plugin:debug](plugin-debug.md) | Display all plugin types, plugin instances of a specific type, or the definition for a specific plugin.
**rest**  |
[rest:debug](rest-debug.md) | Display current rest resource for the application
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Enable a rest resource for the application
**router**  |
[router:debug](router-debug.md) | Exibe as rotas atuais de uma aplicação
[router:rebuild](router-rebuild.md) | Reconstruir rotas de uma aplicação
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Listar todos os sites locais e remotos.
[site:import:local](site-import-local.md) | Import/Configure an existing local Drupal project
[site:install](site-install.md) | Instalar um projeto Drupal
[site:maintenance](site-maintenance.md) | Habilitar/Desabilitar modo de manutenção
[site:mode](site-mode.md) | Atualizar as configurações de desempenho do sistema
[site:new](site-new.md) | Criar um novo projeto Drupal
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Exibir informações da atual instalação do Drupal
**state**  |
[state:debug](state-debug.md) | Exibir as chaves atuais do Estado.
[state:delete](state-delete.md) | Delete State
[state:override](state-override.md) | Sobrescrever a chave de Estado.
**test**  |
[test:debug](test-debug.md) | Listar testes unitários disponíveis para a aplicação.
[test:run](test-run.md) | Executar testes unitários disponíveis para a aplicação
**theme**  |
[theme:debug](theme-debug.md) | Exibir informações sobre os temas da aplicação
[theme:download](theme-download.md) | Baixar um tema para a aplicação
[theme:install](theme-install.md) | Instalar tema(s) na aplicação
[theme:uninstall](theme-uninstall.md) | Desinstalar tema(s) da aplicação
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clean up translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Exibir atualizações necessários para a aplicação
[update:entities](update-entities.md) | Applying Entity Updates
[update:execute](update-execute.md) | Executar uma função especifica de atualização (Update N) de um módulo especifico, ou executar todas
**user**  |
[user:debug](user-debug.md) | Exibe informações dos usuários da aplicação
[user:delete](user-delete.md) | Remover usuários da aplicação
[user:login:clear:attempts](user-login-clear-attempts.md) | Limpar tentativas falhas de login para um usuário.
[user:login:url](user-login-url.md) | Cria uma URL de login de uso único.
[user:password:hash](user-password-hash.md) | Gerar o hash de uma senha em formato texto.
[user:password:reset](user-password-reset.md) | Recuperar senha para um usuário específico.
**views**  |
[views:debug](views-debug.md) | Exibir informações sobre a View atual
[views:disable](views-disable.md) | Desabilitar uma View
[views:enable](views-enable.md) | Habilitar uma View
[views:plugins:debug](views-plugins-debug.md) | Display current views plugins for the application
**yaml**  |
[yaml:diff](yaml-diff.md) | Comparar dois arquivos YAML para determinar diferenças entre eles
[yaml:merge](yaml-merge.md) | Combinar um ou mais arquivos YAML em um único novo arquivo. Os últimos valores serão preservados.
[yaml:split](yaml-split.md) | Dividir o arquivo YAML usando a identação como critério de separação
[yaml:update:key](yaml-update-key.md) | Substituir a chave YAML no arquivo YAML.
[yaml:update:value](yaml-update-value.md) | Atualize o valor para uma chave específica no arquivo YAML.

## Opções disponíveis
Opção | Detalhes
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | <info>%s</info> versão <comment>%s</comment>
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | Nome do ambiente.
--root | Define a rais do Drupal que utilizará os comandos em execução.
--no-debug | Desligar o modo de depuração.
--learning | Gerar código com explicações.
--generate-chain | Imprimir opções e argumentos como YAML para ser usado o comando chain
--generate-inline | Imprimir opções e argumentos de execução como chamada inline para ser usado no futuro
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI do site Drupal para usar (para ambientes multisites ou quando usado em uma porta alternativa)
--yes | Skip confirmation and proceed

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
command | The command to execute
