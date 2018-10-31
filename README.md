# node-twofish-cbc
nodejs module for cbc encryption with the twofish cipher

```js
const twofish = require('twofish');

//encrypt
twofish.enc(password, data)

//decrypt
twofish.dec(password, data)

//encrypt CBC
twofish.encCBC(password, data)

//decrypt
twofish.decCBC(password, data, iv)

//encrypt pbkf2 with cbc 
twofish.encPbkf2(password, salt, iterations, keylen, data)

//decrypt pbkf2 with cbc
twofish.decPbkf2(password, salt, iterations, keylen, data, iv)
```
