# settings:set
Drupal कंसोल कॉन्फिग फाइल में एक विशिष्ट सेटिंग मूल्य बदलें

**प्रयोग:**
```
$ drupal settings:set [arguments] [options]
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--help | Display this help message
--quiet | Suppress all output from the command
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output, and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--no-debug | Switches off debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## उपलब्ध तर्क
तर्क | विवरण
---------|-------------
command | The command to execute
setting-name |  Drupal कंसोल config फाइल में एक मूल्य निर्धारित करने के लिए YAML समतल में सेटिंग नाम का स्थापना
setting-value | सेटिंग वैल्यू Drupal कंसोल config फाइल में स्थापित करने के लिए
