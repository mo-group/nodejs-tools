# sha1

```javascript
var crypto = require('crypto');
```

## encrypt

```javascript
var beforeSHA1 = 'Hello World';

var afterSHA1 = crypto.createHash('sha1').update(beforeSHA1).digest('hex');
```

## decrypt

can't decrypt

## verify

```javascript

if (afterSHA1 === crypto.createHash('sha1').update(beforeSHA1).digest('hex')) {

    // ..
}
```
