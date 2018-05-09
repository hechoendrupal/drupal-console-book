# generate:breakpoint
Generate breakpoint

**Ús:**
```
drupal generate:breakpoint [options]
gb
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--theme | Theme name
--breakpoints | Breakpoints

## Exemples
* Generate a breakpoint specifying the theme, a breakpoint name, its label, the media query, its weight and multipliers
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
