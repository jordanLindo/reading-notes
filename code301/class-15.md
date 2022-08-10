# Reading Notes class-15

Authorization allows content control, preventing users from accessing things that they shouldn't

## What is OAuth

1. A tool for single sign-on across multiple platforms.
2. When we set up accounts on MongoDB it gave us the opportunity to use our google credentials.
3. It uses a limited access token based on the credentials of an alternative authentication tool.
4. It is now an authentication layer of OAuth.

## Authorization and Authentication flows

1. Authentication is identifying a user by some method, and Authorization is access control
2. User chooses to log in on a application, Authorization is checked, User enters credentials, AuthO responds with one-time-use code, AuthO sends the code and credentials to the appropriate server, Server responds with a token, the application uses the token to get the users information. - https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow
3. User chooses to log in on a application, AuthO generates a verifier and challenge, AuthO directs the user to an authorization prompt, User authenticates, AuthO stores the challenge data and sends the user back to the application with a one-time-use code, AuthO sends the code and the verifier to an authorization server, Server checks both the challenge and the verifier, Server responds with a token, the application then uses the token to access the user information. - https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow-with-proof-key-for-code-exchange-pkce
4. A similar flow to the others with a form post a the end to pass the information securely.
5. An system replaces the user in the basic pattern
6. Device Auth add an additional step by sending some code to a device and using it with the credentials to authenticate.
7. User logs into an app which then acts as the user in the basic pattern.
