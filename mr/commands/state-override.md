# state:override
एखाद्या स्थिती की वर अधिशून्य करा.

**Usage:**
```
drupal state:override [arguments]
sto
```

## Available arguments
Argument | Details
---------|-------------
key | अधिलिखित करण्यासाठी स्थिती की.
value | सेट करण्यासाठी स्थिती मूल्य.

## Examples
* Override state value specifying the state name and the new value
```
drupal state:override  comment.node_comment_statistics_scale "!!float 1"
```
