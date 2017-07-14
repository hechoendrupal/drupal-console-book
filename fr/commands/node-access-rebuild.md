# node:access:rebuild
Reconstruit les permissions d'accès aux noeuds. Le processus supprimera tous les privilèges sur le contenu et les remplacera par des permissions basés sur les modules et la configuration actuels.

**application.gitbook.messages.usage:**
```
drupal node:access:rebuild [options]
nar
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--batch | Traiter en mode batch.

## application.gitbook.messages.examples
* Reconstruire les permissions d'accès aux noeuds
```
drupal node:access:rebuild --batch
```
