# generate:help
hook_help() चे लागूकरण उत्पन्न करा.

**वापर:**
```
drupal generate:help [options]
gh
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--description | commands.generate.help.options.description

## उदाहरणे
* मॉड्यूलचे नाव आणि वर्णन दर्शविण्यास हुक मदत उत्पन्न करा.
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
