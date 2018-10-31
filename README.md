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

//decrypt CBC
twofish.decCBC(password, data, iv)
```
