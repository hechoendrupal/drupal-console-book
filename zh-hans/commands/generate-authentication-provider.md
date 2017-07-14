# generate:authentication:provider
生成认证提供者

**Usage:**
```
drupal generate:authentication:provider [options]
gap
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 认证提供者类
--provider-id | 提供者 ID

## Examples
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
