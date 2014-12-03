# md5

## import

```javascript
var crypto = require('crypto');
```

## encrypt

```javascript
var beforeMD5 = 'Hello World';

var afterMD5 = crypto.createHash('md5').update(beforeMD5).digest('hex');
```

## decrypt

can't decrypt

## verify


```javascript

if (afterMD5 === crypto.createHash('md5').update(beforeMD5).digest('hex')) {

    // ..
}
```
