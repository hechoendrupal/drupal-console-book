# generate:breakpoint
生成断点

**使用方法:**
```
drupal generate:breakpoint [options]
gb
```

## 可用选项
选项 | 详细信息
-------|-------------
--theme | 主题名称
--breakpoints | 断点

## 例子
* Generate a breakpoint specifying the theme, a breakpoint name, its label, the media query, its weight and multipliers
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
