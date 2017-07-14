# generate:breakpoint
Generate breakpoint

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:breakpoint [options]
$ gb
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--theme | Theme name
--breakpoints | Breakpoints

## commands.generate.doc.gitbook.messages.examples
* Generate a breakpoint specifying the theme, a breakpoint name, its label, the media query, its weight and multipliers
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
