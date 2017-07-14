# generate:theme
테마를 생성합니다.

**Usage:**
```
drupal generate:theme [options]
gt
```

## Available options
Option | Details
-------|-------------
--theme | commands.generate.theme.options.module
--machine-name | 기계명 (소문자와 밑줄만)
--theme-path | commands.generate.theme.options.module-path
--description | 테마 설명
--core | 코어 버전
--package | 테마 패키지
--global-library | 전역 스타일링 라이브러리 이름
--libraries | commands.generate.theme.options.libraries
--base-theme | 베이스 테마 (예를 들어 classy, stable)
--regions | 지역
--breakpoints | 분절점

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
