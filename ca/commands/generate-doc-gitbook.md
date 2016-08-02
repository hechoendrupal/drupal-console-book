# generate:doc:gitbook
Generar la documentació per els comandaments

**Ús:**
```
$ drupal generate:doc:gitbook [arguments] [options]
$ gdg  
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--path | Camí on renderitzar la documentació
--help | Mostrar aquest missatge d'ajuda
--quiet | No mostrar aquest missatge
--verbose | Augmentar el detall dels missatges: 1 per una sortida normal, 2 per una sortida més detallada i 3 per depurar
--version | <info>"%s"</info> versió <comment>"%s"</comment>
--ansi | Forçar sortida ANSI
--no-ansi | Deshabilitar sortida ANSI
--no-interaction | No fer cap pregunta de forma interactiva
--env | Nom de l'entorn
--root | Definir el camí arrel de Drupal on s'executaran els comandaments
--no-debug | Desactivar el mode de depuració.
--learning | Generar codi detallat.
--generate-chain | Imprimir les opcions d'execució i els arguments com una sortida YAML per ser utilitzats amb el comandament "chain".
--generate-inline | Imprimir les opcions d'execució i els arguments com inserits per ser utilitzats en un futur.
--generate-doc | Mostrar les opcions i arguments dels comandaments com a "markdown"
--target | El nom del lloc web amb el qual vols interactuar (locals o remot)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Ometre la confirmació

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
