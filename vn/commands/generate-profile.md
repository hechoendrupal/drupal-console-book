# generate:profile
Tạo một profile.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | Tên profile
--machine-name | Tên máy (chỉ chữ thường và gạch dưới)
--profile-path | The path of the profile
--description | Mô tả profile
--core | Phiên bản core
--dependencies | Sự phụ thuộc của module chia ra bởi dấu phẩy (ví dụ context, panels)
--themes | the theme name
--distribution | Tên distribution

## Examples
* Generate a profile specifying the profile name, the machine name, a description, the core and its module dependencies
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
