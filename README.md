# url-hash
JavaScript class for easy url hash manipulations

**Installation:**

```npm i simple-url-hash```

**Simple example:**

```js
import Hash from 'Hash';

let urlHash = new Hash();                          
urlHash.set("param1", "value1");
```     

Result url: `your_url#param1=value1`

Methods:
* **set(name, value)** - appends new param or updates an existing param value
* **get(paramName)** - returns value of specified parameter
* **setAll(params)** - doest the same ad set, but for set of parameters ```params = {param1: value1, param2, value2}```
* **removeAll(parameterNames)** - removes all parameters; parameterNames - is an array of parameter names or just one parameter name as string
* **clear()** - removes all parameters 