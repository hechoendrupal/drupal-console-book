# debug:plugin
सर्व प्लगिन प्रकार, एका विशिष्ट प्रकारच्या प्लगिनची उदाहरणे, किंवा विशिष्ट प्लगइनसाठी परिभाषित करा.

**Usage:**
```
drupal debug:plugin [arguments]
dpl
```

## Available arguments
Argument | Details
---------|-------------
type | प्लगिन प्रकार
id | प्लगिन आयडी

## Examples
* Displays a list with all the plugins on the current site
```
drupal debug:plugin
```
* Displays block plugin information
```
drupal debug:plugin block
```
* Displays block broken information
```
drupal debug:plugin block broken
```
