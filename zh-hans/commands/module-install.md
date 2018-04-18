# module:install
安装模块

**使用方法:**
```
drupal module:install [arguments] [options]
moi
```

## 可用选项
选项 | 详细信息
-------|-------------
--latest | 默认下载最新版本
--composer | 使用 Composer卸载模块
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | Switches on debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## 可用参数
参数 | 详细信息
---------|-------------
command | The command to execute
module | 模块间用空格隔开

## 例子
* Install module specifying the module name
```
drupal module:install  modulename
```
