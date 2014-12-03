# base64

## encode

```javascript
var beforeBase64 = 'Hello World';

var afterBase64 = new Buffer(beforeBase64).toString('base64');
```

## decode

```javascript
var afterBase64 = 'SGVsbG8gV29ybGQ=';

var beforeBase64 = new Buffer(afterBase64, 'base64').toString('utf8');
```
