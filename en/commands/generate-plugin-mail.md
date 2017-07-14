# generate:plugin:mail
Generate a plugin mail

**application.gitbook.messages.usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | The Module name.
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin id
--services | Load services from the container.

## application.gitbook.messages.examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
