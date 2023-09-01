## Password encryption
* json web tokens are created in different ways.
* They take an object encrypted in long phase, time of expiration and salt.
* For every request, we will send the token and the server is going to intercept the token and decrypts it.
* If it is able to decypt, then we consider it as Valid token.
* Otherwise, the token is invalid.
