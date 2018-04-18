# chain
链命令执行

**使用方法:**
```
drupal chain [arguments] [options]
```

## 可用选项
选项 | 详细信息
-------|-------------
--file | 用户定义的文件包含要执行的命令。
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
--directory | directory
--language | language

## 可用参数
参数 | 详细信息
---------|-------------
command | The command to execute

## 例子
* 使用完整路径提供文件选项。
```
drupal chain \
  --file="/path/to/file/chain-file.yml"
```
