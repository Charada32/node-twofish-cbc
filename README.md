# node-twofish-cbc
nodejs module for cbc encryption with the twofish cipher

```js
const twofish = require('twofish');

//encrypt
twofish.enc(password, data)

//decrypt
twofish.dec(password, data)

//encrypt CBC
twofish.enc(password, data)

//decrypt
twofish.dec(password, data, iv)

//encrypt pbkf2
twofish.encPbkf2(password, salt, iterations, keylen, data)

//decrypt pbkf2
twofish.decPbkf2(password, salt, iterations, keylen, data, iv)
```
