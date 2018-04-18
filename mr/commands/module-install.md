# module:install
अनुप्रयोग मध्ये मॉड्यूल किंवा मॉड्यूल स्थापित.

**वापर:**
```
drupal module:install [arguments] [options]
moi
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--latest | सर्वात अलीकडील आवृत्ती डाउनलोड करण्यासाठी डीफॉल्ट.
--composer | Composer वापरून मॉड्यूल विस्थापित करते.
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

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
command | The command to execute
module | सक्षम केलेल्या मोड्यूल किंवा मॉड्यूल्सना स्पेसद्वारे विभक्त व्हायला हवे.

## उदाहरणे
* मॉड्युलचे नाव निर्दिष्ट करणारी मॉड्यूल प्रतिष्ठापित करा.
```
drupal module:install  modulename
```
