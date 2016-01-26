# generate:doc:gitbook
**generate:doc:gitbook** 命令 生成命令文档

**用法:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## 可用选项
选项 | 详细
-------|-------------
--path | 呈现文档的路径
--help | 显示帮助
--quiet | 静默模式，不输出任何消息
--verbose | 消息输出。 v：正常输出，vv：详细输出，vvv：调试输出
--version | 显示程序版本
--ansi | 强制 ANSI 输出
--no-ansi | 禁用 ANSI 输出
--no-interaction | 无交互问题
--env | 环境名称
--root | 定义 Drupal 根目录，命令执行时使用
--no-debug | 禁用调试
--learning | 生成详细的代码输出用于学习
--generate-chain | 以 YAML 格式显示命令执行时的选项和参数，用于链式执行一组命令
--generate-inline | 将命令执行时的选项和参数显示成一行，以便后续使用
--generate-doc | 显示命令选项和参数为 markdown 格式
--target | 与之交互的站点名字（本地或远程网站）
--uri | Drupal 网站的 URI( 用于多站点环境或运行在不同的端口)
--yes | 跳过确认并继续

## 可用参数
参数 | 详细
---------|-------------
command | 执行的命令
