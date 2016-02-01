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
--learning | Generar codi detalladament (verbose).
--generate-chain | Imprimir les opcions d'execució i els arguments com una sortida de YAML per ser utilitzats amb el comandament "chain".
--generate-inline | Imprimir les opcions d'execució i els arguments com inserits (inline) per ser utilitzats en un futur
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI del lloc web Drupal que s'utilitzarà (per entorns "multisite" o quan s'utilitza un port alternatiu)
--yes | Skip confirmation and proceed

## Arguments disponibles
Argument | Detalls
---------|-------------
command | El comandament a executar
