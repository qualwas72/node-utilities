node-utitlies
=============
a generic utilities library for node.js

# Installation

Install and use it via npm + git. 

`npm install git+ssh://git@github.com:limianwang/node-utitlies.git --save`

# Usage

```javascript
var util = require('./');

var obj = {
  key: 'value',
  key2: {
    field : ['a','b']
  }
};

var cloned = util.clone(obj);
```

# Tests

All tests are within `tests`. Run using `npm test`