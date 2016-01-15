# 使用 Composer 安装 Drupal Console
你可以使用 composer 进行安装。

## 全局安装：
```
$ composer global require drupal/console:@stable
```

## 添加 bin 文件夹到系统 path 环境变量中：
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## 现在你可以使用它了。例如：生成一个模块：
```
$ drupal generate:module
```
