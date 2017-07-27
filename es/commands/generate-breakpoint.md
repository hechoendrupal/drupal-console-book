# generate:breakpoint
Genera un breakpoint

**Uso:**
```
drupal generate:breakpoint [options]
gb
```

## Opciones disponibles
Opción | Detalles
-------|-------------
--theme | Nombre del tema
--breakpoints | Breakpoints

## Ejemplos
* Generar un breakpoint especificando el theme, nombre del breakpoint, su etiqueta, la media query, su peso y sus múltiplos
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
