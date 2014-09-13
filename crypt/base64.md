# base64

## encode

    var beforeBase64 = 'Hello World';

    var afterBase64 = new Buffer(beforeBase64).toString('base64');

## decode

    var afterBase64 = 'SGVsbG8gV29ybGQ=';

    var beforeBase64 = new Buffer(afterBase64, 'base64').toString('utf8');