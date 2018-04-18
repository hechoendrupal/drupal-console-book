# Comandos Drupal Console Disponíveis

**Note:** Comandos Drupal Console *devem* ser excutados a partir da raíz de uma instalação Drupal 8.

Comando Drupal Console | Detalhes
------------ | -------------
**misc**  |
[about](about.md) | Exibir informações básicas sobre projeto Drupal Console
[chain](chain.md) | Execução de comandos em sequência
[check](check.md) | Verificador de requisitos do sistema
[composerize](composerize.md) | Converts Drupal codebase to composer.
[exec](exec.md) | Execute an external command.
[help](help.md) | Displays help for a command
[init](init.md) | Copy configuration files to user home directory.
[list](list.md) | Lists commands22
[shell](shell.md) | Open a shell providing an interactive REPL (Read–Eval–Print-Loop).
[server](server.md) | Executar o servidor PHP atual
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruir e limpar todos os caches do site.
[cache:tag:invalidate](cache-tag-invalidate.md) | Invalidate cache tags.
**config**  |
[config:delete](config-delete.md) | Remove configuração
[config:diff](config-diff.md) | Mostra os itens de configuração que são diferentes na configuração ativa em comparação com um diretório.
[config:edit](config-edit.md) | Edite a configuração selecionada.
[config:export](config-export.md) | Exportar a configuração atual da aplicação.
[config:export:content:type](config-export-content-type.md) | Exportar um tipo de conteúdo específico e os seus campos.
[config:export:single](config-export-single.md) | Exportar configuração como um arquivo yml.
[config:export:view](config-export-view.md) | Exportar uma view no formato YAML dentro de um módulo fornecido para reutilização em outro site.
[config:import](config-import.md) | Importar configuração do estado atual da aplicação.
[config:import:single](config-import-single.md) | Importar a configuratição selecionada.
[config:override](config-override.md) | Sobrescrever valor de configuração ativa.
[config:validate](config-validate.md) | Validate a drupal config against its schema
**config_update**  |
[config_update:default](config_update-default.md) | commands.config_update.default.description
**create**  |
[create:comments](create-comments.md) | Criar comentários dummy para sua aplicação Drupal 8.
[create:nodes](create-nodes.md) | Create dummy nodes for your Drupal 8 application.
[create:roles](create-roles.md) | Create dummy roles for your Drupal 8 application.
[create:terms](create-terms.md) | Create dummy terms for your Drupal 8 application.
[create:users](create-users.md) | Create dummy users for your Drupal 8 application.
[create:vocabularies](create-vocabularies.md) | Create dummy vocabularies for your Drupal 8 application.
**cron**  |
[cron:execute](cron-execute.md) | Executar cron de um módulo específico ou todos para executar todas as implementações
[cron:release](cron-release.md) | Desbloquear cron para voltar a executar
**database**  |
[database:add](database-add.md) | Add a database to settings.php
[database:client](database-client.md) | Iniciar um cliente de banco de dados se ele está disponível
[database:connect](database-connect.md) | Iniciar um cliente de banco de dados se ele está disponível
[database:drop](database-drop.md) | Drop all tables in a given database.
[database:dump](database-dump.md) | Dump da estrutura e conteúdos da base de dados e tabelas MySQL
[database:log:clear](database-log-clear.md) | Remove eventos da tabela DBLog, filtros disponíveis
[database:log:poll](database-log-poll.md) | Poll the watchdog and print new log entries every x seconds
[database:query](database-query.md) | Executes a SQL statement directly as argument
[database:restore](database-restore.md) | Restaurar a estrutura e conteúdo das bases de dados e tabelas do MySQL
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | Exibe breakpoints disponíveis na aplicação
[debug:cache:context](debug-cache-context.md) | Displays current cache context for the application.
[debug:chain](debug-chain.md) | List available chain files.
[debug:config](debug-config.md) | Exibe a configuração atual.
[debug:config:settings](debug-config-settings.md) | Displays current key:value on settings file.
[debug:config:validate](debug-config-validate.md) | Validate a schema implementation before a module is installed.
[debug:container](debug-container.md) | Exibe serviços atuais para um aplicativo.
[debug:cron](debug-cron.md) | Lista de módulos quem implementam uma chamada no cron
[debug:database:log](debug-database-log.md) | Exibir eventos de log atuais do aplicativo
[debug:database:table](debug-database-table.md) | Show all tables in a given database.
[debug:entity](debug-entity.md) | Debug entities available in the system
[debug:event](debug-event.md) | Display current events 
[debug:features](debug-features.md) | List registered features.
[debug:image:styles](debug-image-styles.md) | List image styles on the site
[debug:libraries](debug-libraries.md) | Displays libraries available in application
[debug:migrate](debug-migrate.md) | Display current migration available for the application
[debug:module](debug-module.md) | Display current modules available for application
[debug:multisite](debug-multisite.md) | Listar todos os multi-sites disponíveis no sistema
[debug:permission](debug-permission.md) | Displays all user permissions.
[debug:plugin](debug-plugin.md) | Mostra todos os tipos de plugins, instâncias de um tipo específico de plugin ou a definição para um plugin específico.
[debug:queue](debug-queue.md) | Display the queues of your application
[debug:rest](debug-rest.md) | Exibir o recurso REST atual para a aplicação
[debug:roles](debug-roles.md) | Displays current roles for the application
[debug:router](debug-router.md) | Exibe as rotas atuais de uma aplicação
[debug:settings](debug-settings.md) | Lista configurações do Drupal Console do usuário
[debug:site](debug-site.md) | Listar todos os sites locais e remotos.
[debug:state](debug-state.md) | Exibir as chaves atuais de Estado.
[debug:test](debug-test.md) | Listar testes unitários disponíveis para a aplicação.
[debug:theme](debug-theme.md) | Exibir informações sobre os temas da aplicação
[debug:theme:keys](debug-theme-keys.md) | Displays all theme keys provided by hook_theme functions
[debug:update](debug-update.md) | Exibir atualizações necessários para a aplicação
[debug:user](debug-user.md) | Exibe informações dos usuários da aplicação
[debug:views](debug-views.md) | Exibir informações sobre a View atual
[debug:views:plugins](debug-views-plugins.md) | Mostrar os plugins de views atuais para a aplicação
**devel**  |
[devel:dumper](devel-dumper.md) | commands.devel.dumper.messages.change-devel-dumper-plugin
**docker**  |
[docker:init](docker-init.md) | Create a docker-compose.yml file
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | Debug Dotenv debug values.
[dotenv:init](dotenv-init.md) | Dotenv initializer.
**entity**  |
[entity:delete](entity-delete.md) | Delete an specific entity
**features**  |
[features:import](features-import.md) | Import module config.
**field**  |
[field:info](field-info.md) | View information about fields.
**generate**  |
[generate:ajax:command](generate-ajax-command.md) | Generate & Register a custom ajax command
[generate:authentication:provider](generate-authentication-provider.md) | Gerar um provedor de autenticação
[generate:breakpoint](generate-breakpoint.md) | Generate breakpoint
[generate:cache:context](generate-cache-context.md) | Generate a cache context
[generate:command](generate-command.md) | Cria comandos via console.
[generate:controller](generate-controller.md) | Cria e Registra um controller
[generate:entity:bundle](generate-entity-bundle.md) | Gera um novo tipo de conteúdo (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | Gerar uma nova entidade de configuração
[generate:entity:content](generate-entity-content.md) | Gerar uma nova entidade de conteúdo
[generate:event:subscriber](generate-event-subscriber.md) | Gerar um assinante do evento
[generate:form](generate-form.md) | Generate a new "FormBase"
[generate:form:alter](generate-form-alter.md) | Gera uma implementação de hook_form_alter() ou hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generate a new "ConfigFormBase"
[generate:help](generate-help.md) | Generate an implementation of hook_help()
[generate:jstest](generate-jstest.md) | Generate a JavaScript test.
[generate:module](generate-module.md) | Criar um módulo.
[generate:module:file](generate-module-file.md) | Generate a .module file
[generate:permissions](generate-permissions.md) | Generate module permissions
[generate:plugin:block](generate-plugin-block.md) | Criar plugin de bloco.
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | Gerar um Plugin de botão CKEditor.
[generate:plugin:condition](generate-plugin-condition.md) | Criar um plugin de condition.
[generate:plugin:field](generate-plugin-field.md) | Gera plugins de widgets, fortmato e tipo de campo
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Gerar um plugin de formato de campo.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Gerar um plugin de tipo de campo
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Generate field widget plugin.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Criar plugin de efeito de imagem.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Generate image formatter plugin.
[generate:plugin:mail](generate-plugin-mail.md) | Generate a plugin mail
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | Generate a migrate process plugin
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | Generate a migrate source plugin
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Generate plugin rest resource
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Generate a plugin rule action
[generate:plugin:skeleton](generate-plugin-skeleton.md) | Generate an implementation of a skeleton plugin for those plugins Drupal Console do not have a specific generator
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Generate a plugin type with annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Generate a plugin type with Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | Generate a custom plugin view field.
[generate:post:update](generate-post-update.md) | Generate an implementation of hook_post_update_NAME()
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generate a RouteSubscriber
[generate:service](generate-service.md) | Criar serviço
[generate:site:alias](generate-site-alias.md) | Generates a site alias.
[generate:theme](generate-theme.md) | Generate a theme.
[generate:twig:extension](generate-twig-extension.md) | Generate a Twig extension.
[generate:update](generate-update.md) | Generate an implementation of hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | Execute flush function by image style or execute all flush images styles
**locale**  |
[locale:language:add](locale-language-add.md) | Add a language to be supported by your site
[locale:language:delete](locale-language-delete.md) | DElete a language to be supported by your site
[locale:translation:status](locale-translation-status.md) | List available translation updates
**migrate**  |
[migrate:execute](migrate-execute.md) | Execute a migration available for application
[migrate:rollback](migrate-rollback.md) | Rollback one or multiple migrations
[migrate:setup](migrate-setup.md) | Load and create the relevant migrations for a provided legacy database
**module**  |
[module:dependency:install](module-dependency-install.md) | Install dependencies module in the application
[module:download](module-download.md) | Download module or modules in application
[module:install](module-install.md) | Instala módulo(s) na aplicação
[module:path](module-path.md) | Returns the relative path to the module (or absolute path)
[module:uninstall](module-uninstall.md) | Desinstala módulos ou módulos na aplicação
[module:update](module-update.md) | Update core, module or modules in the application
**multisite**  |
[multisite:new](multisite-new.md) | Sets up the files for a new multisite install.
[multisite:update](multisite-update.md) | Update the files for a multisite installed.
**node**  |
[node:access:rebuild](node-access-rebuild.md) | Permissões de acesso ao node reconstruídas. A reconstrução irá remover todos os privilégios do conteúdo e substituí-los com permissões baseadas nos módulos e configurações atuais.
**queue**  |
[queue:run](queue-run.md) | Process the selected queue.
**rest**  |
[rest:disable](rest-disable.md) | Disable a rest resource for the application
[rest:enable](rest-enable.md) | Habilite um recurso REST para a aplicação
**role**  |
[role:delete](role-delete.md) | Delete roles for the application
[role:new](role-new.md) | Create roles for the application
**router**  |
[router:rebuild](router-rebuild.md) | Reconstruir rotas de uma aplicação
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:import:local](site-import-local.md) | Importar/Configurar um projeto local existente do Drupal
[site:install](site-install.md) | Instalar um projeto Drupal
[site:maintenance](site-maintenance.md) | Habilitar/Desabilitar modo de manutenção
[site:mode](site-mode.md) | Atualizar as configurações de desempenho do sistema
[site:statistics](site-statistics.md) | Exibe as estatísticas atuais para o website.
[site:status](site-status.md) | Exibir informações da atual instalação do Drupal
**state**  |
[state:delete](state-delete.md) | Apagar Estado
[state:override](state-override.md) | Sobrescrever a chave de Estado.
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | Delete taxonomy terms from a vocabulary
**test**  |
[test:run](test-run.md) | Executar testes unitários disponíveis para a aplicação
**theme**  |
[theme:download](theme-download.md) | Baixar um tema para a aplicação
[theme:install](theme-install.md) | Instalar tema(s) na aplicação
[theme:path](theme-path.md) | Returns the relative path to the theme (or absolute path)
[theme:uninstall](theme-uninstall.md) | Desinstalar tema(s) da aplicação
**update**  |
[update:entities](update-entities.md) | Aplicando atualização de entidades
[update:execute](update-execute.md) | Executar uma função especifica de atualização (Update N) de um módulo especifico, ou executar todas
**user**  |
[user:create](user-create.md) | Create users for the application
[user:delete](user-delete.md) | Remover usuários da aplicação
[user:login:clear:attempts](user-login-clear-attempts.md) | Limpar tentativas falhas de login para um usuário.
[user:login:url](user-login-url.md) | Cria uma URL de login de uso único.
[user:password:hash](user-password-hash.md) | Gerar o hash de uma senha em formato texto.
[user:password:reset](user-password-reset.md) | Recuperar senha para um usuário específico.
[user:role](user-role.md) | Adds/removes a role for a given user
**views**  |
[views:disable](views-disable.md) | Desabilitar uma View
[views:enable](views-enable.md) | Habilitar uma View

## Opções disponíveis
Opção | Detalhes
-------|-------------
--help | Exibir essa mensagem de ajuda
--quiet | Não mostrar nenhuma mensagem de saída
--verbose | Aumentar detalhamento das mensagens: 1 para saída normal, 2 para saída mais detalhada e 3 para depurar
--version | <info>%s</info> versão <comment>%s</comment>
--ansi | Forçar saída ANSI
--no-ansi | Desabilitar saída ANSI
--no-interaction | Não faça nenhuma pergunta interativa
--env | Nome do ambiente.
--root | Define a raíz do Drupal que utilizará os comandos em execução.
--debug | Switches on debug mode
--learning | Gerar código com explicações.
--generate-chain | Imprimir opções e argumentos como YAML para ser usado o comando chain
--generate-inline | Imprimir opções e argumentos de execução como chamada inline para ser usado no futuro
--generate-doc | Mostra opções de comando e argumentos como markdown
--target | Nome do site com o qual deseja interagir (para sites locais ou remotos)
--uri | URI do site Drupal para usar (para ambientes multisites ou quando usado em uma porta alternativa)
--yes | Pular confirmação e prosseguir

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
command | O comando a ser executado
