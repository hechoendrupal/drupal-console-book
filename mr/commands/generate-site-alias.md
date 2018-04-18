# generate:site:alias
Generates a site alias.

**वापर:**
```
drupal generate:site:alias [options]
gsa
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--site | Use local site as destination.
--name | Site name.
--environment | Environment name.
--type | The site type.
--composer-root | The Drupal root project directory.
--site-uri | Drupal uri (for multi-sites).
--host | The ip/domain name of the remote system. Not required on local sites.
--user | The username to use when connecting via ssh.
--port | The port to use when connecting via ssh.
--extra-options | Used only when the target requires extra options, such as alternative authentication method and/or alternative identity file.
--directory | Directory to store the generated site alias.
