# cryptography


```js
const CryptoJS = require('crypto-js');

const secretKey = ''; // password here
const encryptedData = '';

const decryptedData = CryptoJS.AES.decrypt(encryptedData, secretKey).toString(
  CryptoJS.enc.Utf8,
);

console.log('file: index.js:14  original message', decryptedData);
```
