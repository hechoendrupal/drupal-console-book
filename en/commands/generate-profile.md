# generate:profile
Generate a profile.

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:profile [options]
$ gpr  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--profile | The profile name
--machine-name | The machine name (lowercase and underscore only)
--description | Profile description
--core | Core version
--dependencies | Module dependencies separated by commas (i.e. context, panels)
--themes | commands.generate.profile.options.themes
--distribution | The distribution name

## commands.generate.doc.gitbook.messages.examples
* Generate a profile specifying the profile name, the machine name, a description, the core and its module dependencies
```
$ drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"

```
