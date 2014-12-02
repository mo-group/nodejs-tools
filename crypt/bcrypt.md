# bcrypt

use [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js/)

## install

```bash
npm install --save bcrypt
```

## import

```javascript
var bcrypt = require('bcrypt');
```

## encrypt

```javascript
var beforeHash = 'Hello World';

bcrypt.genSalt(10, function(err, salt) {
    bcrypt.hash(beforeHash, salt, function(err, hashed) {
        // Store hash in your password DB.
    });
});
```

## decrypt

can't decrypt

## verify

```javascript
var beforeHash = 'Hello World';

bcrypt.compare(beforeHash, hashed, function(err, res) {

    // res : true or false
});
```
