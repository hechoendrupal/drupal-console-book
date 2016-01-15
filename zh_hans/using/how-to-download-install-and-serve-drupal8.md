# 如何下载，安装并运行 Drupal 8

最简单的方式就是在本地执行 `chain` 命令，并且将 `--file=~/.console/chain/quick-start.yml` 选项传递给它。示例如下：

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> 注意: 你必须先执行 `drupal init` 命令，该命令会拷贝 `quick-start.yml` 到 `~/.console/chain/quick-start.yml`

`chain` 命令帮助你自动执行命令，它允许你定义一个包含多条命令的外部 YAML 文件，这个文件中的每条命令，由命令的名称、选项和参数组成，命令在文件中的顺序即为执行顺序

默认 `~/.console/chain/quick-start.yml` 文件中的内容：
```
commands:
  - command: site:new
    arguments:
      site-name: drupal8.dev
      version: 8.0.0
  - command: site:install
    options:
        root: /Users/jmolivas/develop/drupal/sites/drupal8.dev
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

在这个例子中，会下载和使用 SQLite 安装 Drupal，最后会启动 PHP 内建服务器。然后，你只需要打开浏览器，访问 127.0.0.1:8088 就可以了.

你可以复制或修改提供这个 YAML 文件，添加任意命令，如下载模块 `module:download`，安装模块 `module:install` ，导入配置 `config:import` 以及还原数据库 `database:restore` 或其他任何 Drupal Console 提供的命令或者你自己的模块提供的自定义命令。
