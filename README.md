# todos-express-google

This app illustrates how to use [Passport](https://www.passportjs.org/) with
[Express](https://expressjs.com/) to sign users in with [Google](https://www.google.com/).
Use this example as a starting point for your own web applications.

## Quick Start

To run this app, clone the repository and install dependencies:

```bash
$ git clone https://github.com/anilkarela/google-login-using-passportjs
$ cd google-login-using-passportjs
$ npm install
```

This app requires OAuth 2.0 credentials from Google, which can be obtained by
[setting up](https://developers.google.com/identity/protocols/oauth2/openid-connect#appsetup)
a project in [Google API console](https://console.developers.google.com/apis/).
The redirect URI of the OAuth client should be set to `'http://localhost:3000/oauth2/redirect/google'`.

Once credentials have been obtained, create a `.env` file and add the following
environment variables:

```
GOOGLE_CLIENT_ID=__INSERT_CLIENT_ID_HERE__
GOOGLE_CLIENT_SECRET=__INSERT_CLIENT_SECRET_HERE__
```

Start the server.

```bash
$ npm start
```

Navigate to [`http://localhost:3000`](http://localhost:3000).
