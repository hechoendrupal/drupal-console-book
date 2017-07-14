# generate:breakpoint
ब्रेकपॉईंट उत्पन्न करा.

**Usage:**
```
drupal generate:breakpoint [options]
gb
```

## Available options
Option | Details
-------|-------------
--theme | थीम नाव
--breakpoints | ब्रेकपॉइंट

## Examples
* Generate a breakpoint specifying the theme, a breakpoint name, its label, the media query, its weight and multipliers
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
