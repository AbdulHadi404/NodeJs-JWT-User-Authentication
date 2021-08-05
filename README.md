# NodeJs-JWT-User-Authentication

Authentication performed using Json Web Tokens and password hashing using bcrypt

### To Generate Token Strings

Generated the encrypted keys for Tokens using crypto for setting up environment variables

```js
require('crypto').randomBytes(64).toString('hex');
```
