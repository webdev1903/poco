Node-Express-MongoDB backend server.

## Available Routes

- /register - user can register by providing name, email and password.
- /login - user can login by providing email and password.
- / - user can add and deleted tasks after logging in, jwt token has to provided for authorization.
- /refreshToken - refresh-token mechanism has been implemented, where the jwt token will be expired every 7 minutes and new token will be genereated for better security.

## Available Scripts

In the project directory, you can run:

### `npm start` or 'node index.js' to start the server




