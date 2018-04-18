# generate:profile
生成一个方案.

**使用方法:**
```
drupal generate:profile [options]
gpr
```

## 可用选项
选项 | 详细信息
-------|-------------
--profile | 方案名
--machine-name | 机读名称(只允许下划线和小写英文字母)
--profile-path | The path of the profile
--description | 方案介绍
--core | Drupal内核版本
--dependencies | 依赖模块用逗号隔开(例如： context, panels)
--themes | the theme name
--distribution | Drupal安装套餐名

## 例子
* Generate a profile specifying the profile name, the machine name, a description, the core and its module dependencies
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
