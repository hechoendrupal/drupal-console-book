# generate:doc:gitbook
El comandament **generate:doc:gitbook** executa Generar documentació per els comandaments

**Ús:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--path | Ruta on renderitzar la documentació
--learning | Generar codi detalladament (verbose).
--help | Mostra aquest missatge d'ajuda
--quiet | No mostrar cap missatge
--verbose | Augmentar el detall dels missatges: 1 per una sortida normal, 2 per obtenir més detall i 3 per depurar
--version | Mostra la versió d'aquesta applicació
--ansi | Forçar la sortida ANSI
--no-ansi | Deshabilitar la sortida ANSI
--no-interaction | No preguntar res de forma interactiva
--env | Nom de l'entorn.
--root | Definir la ruta arrel de Drupal on s'executaran els comandaments
--no-debug | Desactivar el mode de depuració (debug).
--generate-chain | Imprimir les opcions d'execució i els arguments com una sortida de YAML per ser utilitzats amb el comandament "chain".
--generate-inline | Imprimir les opcions d'execució i els arguments com inserits (inline) per ser utilitzats en un futur
--generate-doc | Mostrar les opcions i arguments dels comandaments com a "markdown"
--target | El nom del lloc web amb el qual vols interactuar (llocs locals o remots)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Continuar ometent la confirmació

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
