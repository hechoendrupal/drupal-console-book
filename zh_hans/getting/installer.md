# 使用 Drupal Console 安装器
你可以使用安装器安装 Drupal Console

## 使用 curl：
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
```
## 如果没有 curl:
```
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## 现在你可以这样使用：
```
$ php drupal.phar
```

你可以将这个文件放到你的 PATH 环境变量中的某个文件夹中，然后就可以在系统的任何地方访问这个文件了。对于类 Unix 系统，你可以给这个文件添加可执行权限，不必再输入 php 。

### 系统的任何地方都可以访问
```
$ mv drupal.phar /usr/local/bin/drupal
```

### 添加可执行权限
```
$ chmod +x /usr/local/bin/drupal
```

#### 现在你可以执行:
```
$ drupal
```

**注意:** `drupal` 仅仅是个别名，你可以改为其他任何你喜欢的名字
