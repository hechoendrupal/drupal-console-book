# generate:doc:gitbook
O **generate:doc:gitbook** comando Gerar documentação para os comandos

**Uso:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--path | O caminho para exportar a documentação
--learning | Gerar código com explicações.
--help | Exibir mensagens de ajuda.
--quiet | Não exibir nenhuma mensagem.
--verbose | Detalhar as mensagens de saída: 1 para normal, 2 para  mais detalhes e 3 para debug.
--version | Mostra a versão desta aplicação.
--ansi | Forçar saida ANSI
--no-ansi | Desabilitar saída ANSI
--no-interaction | Não exibir perguntas de interação.
--env | Nome do ambiente.
--root | Define a rais do Drupal que utilizará os comandos em execução.
--no-debug | Desligar o modo de depuração.
--generate-chain | Imprimir opções e argumentos como YAML para ser usado o comando chain
--generate-inline | Imprimir opções e argumentos de execução como chamada inline para ser usado no futuro
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI do site Drupal para usar (para ambientes multisites ou quando usado em uma porta alternativa)
--yes | Skip confirmation and proceed

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
command | O comando para executar.
