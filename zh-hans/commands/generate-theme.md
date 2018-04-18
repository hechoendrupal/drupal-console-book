# generate:theme
生成一个外观主题.

**使用方法:**
```
drupal generate:theme [options]
gt
```

## 可用选项
选项 | 详细信息
-------|-------------
--theme | 主题名
--machine-name | 机读名称(小写字母和下划线)
--theme-path | 主题路径
--description | 外观主题介绍
--core | 内核版本
--package | 外观主题包
--global-library | 全局格式库名
--libraries | Libraries
--base-theme | 基础外观主题 (例如： classy, stable)
--regions | 区域
--breakpoints | 断点

## 例子
* Generate a theme without region and without breakpoint specifying the theme name, its machine name, the theme path, a description, the drupal core, the package name and the global library
```
drupal generate:theme  \
  --theme="AnotherTheme"  \
  --machine-name="anothertheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="PackageName"  \
  --global-library="global-styling"  \
  --base-theme="false"
```
* Generate a theme base on stable theme with two region defined and one breakpoint specifying the theme name, its machine name, the theme path, a description, the drupal core, the package name, a global library, its base, the regions and the breakpoint
```
drupal generate:theme  \
  --theme="MyTheme"  \
  --machine-name="mytheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="MyThemePackage"  \
  --global-library="global-styling"  \
  --base-theme="stable"  \
  --regions='"region_name":"Content", "region_machine_name":"content"'  \
  --regions='"region_name":"Panel", "region_machine_name":"panel"'  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
