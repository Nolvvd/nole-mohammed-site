A simple web page that demonstrates Federated Identity Management using Google as an Identity Provider (IdP).
What it does

Displays my name and a personal landing page
Allows users to sign in using their Google account
Uses Google OAuth 2.0 / OpenID Connect — no passwords are stored locally
After sign-in, shows the user's name, email, and profile photo from Google

How it works
This project uses the Federated Identity Management model:

Identity Provider (IdP): Google — handles authentication and verifies the user's identity
Service Provider (SP): This website — receives a signed JWT token from Google and grants access
The user never creates a username or password on this site
