# OAuth
OAuth (Open Authorization) is an open standard authorization framework for token-based authorization on the internet. OAuth, which is pronounced "oh-auth," enables an end user's account information to be used by third-party services, such as Facebook and Google, without exposing the user's account credentials to the third party. It acts as an intermediary on behalf of the end user, providing the third-party service with an access token that authorizes specific account information to be shared. The process for obtaining the token is called an authorization flow.


![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCFSmIJnKd0tesRcNxDslNSwaG3wYIXDQk_A&usqp=CAU)

### OAuth Examples:

The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website’s login?” In this scenario, the only thing the first website – let’s refer to that website as the consumer – wants to know is that the user is the same user on both websites and has logged in successfully to the service provider – which is the site the user initially logged into, not the consumer.

Facebook apps are a good OAuth use case example. Say you’re using an app on Facebook, and it asks you to share your profile and pictures. Facebook is, in this case, the service provider: it has your login data and your pictures. The app is the consumer, and as the user, you want to use the app to do something with your pictures. You specifically gave this app access to your pictures, which OAuth is managing in the background.

Your smart home devices – toaster, thermostat, security system, etc. – probably use some kind of login data to sync with each other and allow you to administer them from a browser or client device. These devices use what OAuth calls confidential authorization. That means they hold onto the secret key information, so you don’t have to log in over and over again.

### What is OpenID? | OpenID

OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords. You may choose .

What is the difference between authorization and authentication?
 Auth0 uses the OpenID Connect (OIDC) Protocol and OAuth 2.0 Authorization Framework to authenticate users and get their authorization to access protected resources. With Auth0, you can easily support different flows in your own applications and APIs without worrying about OIDC/OAuth 2.0 specifications or other technical aspects of authentication and authorization. We support scenarios for server-side, mobile, desktop, client-side, machine-to-machine, and device applications.

What is Authorization Code Flow?
Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.

Authorization Code Flow
Add Login Using the Authorization Code Flow
Call API Using the Authorization Code Flow
What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).

Authorization Code Flow with Proof Key for Code Exchange (PKCE)
Add Login Using the Authorization Code Flow with PKCE
Call API Using the Authorization Code Flow with PKCE
What is Implicit Flow with Form Post?
s an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication.

Implicit Flow with Form Post
Add Login Using the Implicit Flow with Form Post
Authenticate SPAs with Cookies
What is Client Credentials Flow?
With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4).

Client Credentials Flow
Call API Using the Client Credentials Flow
What is Device Authorization Flow?
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (drafted in OAuth 2.0). For use with mobile/native applications.

Device Authorization Flow
Call API Using the Device Authorization Flow
What is Resource Owner Password Flow?
Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.

Resource Owner Password Flow
Call API Using the Resource Owner Password Flow
