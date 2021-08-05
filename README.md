# NodeJs-JWT-User-Authentication
 Authentication performed using Json Web Tokens and password hashing using bcrypt

### To Generate Token Strings

Use a new terminal to generate the encrypted keys for Tokens

```js
$ node
require('crypto').randomBytes(64).toString('hex')
```
