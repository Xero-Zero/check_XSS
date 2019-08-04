# Check_XSS 

## check_xss.py

__How to execute:__


```
python3 check_xss.py -url "http://victim/?param1=test&param2=test2&foo=bar" -payload '[XSS"]'
```

This script...

- searches for inputs, textareas, selects, buttons and uses their name/id values as additional get parameters
- replaces every get value with the given payload and checks if its reflected in the http body

Optional parameters:

- payload

