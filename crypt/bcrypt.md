# bcrypt

use [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js/)

install:

    npm install --save bcrypt

import:

    var bcrypt = require('bcrypt');

## encode

    var beforeHash = 'Hello World';

    bcrypt.genSalt(10, function(err, salt) {
        bcrypt.hash(beforeHash, salt, function(err, hashed) {
            // Store hash in your password DB.
        });
    });

## decode

can't decode

## check

    var beforeHash = 'Hello World';

    bcrypt.compare(beforeHash, hashed, function(err, res) {

        // res : true or false
    });