# generate:authentication:provider
生成认证提供者

**使用方法:**
```
drupal generate:authentication:provider [options]
gap
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 认证提供者类
--provider-id | 提供者 ID

## 例子
* Generate an authentication provider specifying the module, the class and the provider id
```
drupal generate:authentication:provider  \
  --module="modulename"  \
  --class="DefaultAuthenticationProvider"  \
  --provider-id="default_authentication_provider"
```
