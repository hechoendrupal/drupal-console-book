# 如何拷贝配置文件
Drupal Console 安装完成后的第一件事就是执行 `init` 命令。执行这个命令将拷贝项目配置文件到你的 `~/.console/` 文件夹。 覆写 被拷贝文件中的值，就可以改变 Drupal Console 的行为。

 ```
 $ drupal init [--override]
 ```
 
### 执行 `init` 命令时被拷贝的文件
```
 ~/.console/ 
 ├── aliases.yml 
 ├── chain
 │   ├── quick-start.yml
 │   └── sample.yml 
 ├── config.yml 
 ├── console.rc 
 ├── drupal.fish 
 └── sites 
     └── sample.yml 
```
