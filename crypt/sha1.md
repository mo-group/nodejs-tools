# sha1

    var crypto = require('crypto');

## encode

    var beforeSHA1 = 'Hello World';

    var afterSHA1 = crypto.createHash('sha1').update(beforeSHA1).digest('hex');

## decode

can't decode

## verify
