# generate:theme
Tạo một theme.

**Usage:**
```
drupal generate:theme [options]
gt
```

## Available options
Option | Details
-------|-------------
--theme | Tên của theme
--machine-name | Tên máy (chỉ sử dụng chữ thường và dấu gạch dưới)
--theme-path | Đường dẫn của theme
--description | Mô tả của theme
--core | Phiên bản Core
--package | Gói theme
--global-library | Tên thư viện style chung
--libraries | Libraries
--base-theme | Theme cơ sở (i.e. classy, stable)
--regions | Regions
--breakpoints | Breakpoints

## Examples
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
