# Authentication  

## What is [OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)  

1. OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.  

2. When you got to log into a website, and it offers one or more opportunities to log on using another website's logon. You then click the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permmission gained from the second website.  

3. OAuth works by gaining a user authorization through a different website through authentication processes (ie: password), which then responds with an authorization that the user has been authenticated.  

- First website connects to the second website for the user using OAuth and providing the user's verified identity  
- Second site generates a one-time token and a one-time secret unique to the transaction and parties involved  
- First site gives this token and secret to the initiating user's client software  
- Client's software presents the request token and secret to their authorization provider  
- If not already authenticated to the authorization provider, client may be asked to authenticate. After authentication, client is asked to approve the authorization transaction to the second website  
- User approves (or their software approves) a particular transaction type at the first website  
- User is given an approved access token  
- User gives the approved access token to the first website  
- First website gives access token to the second website as proof of authentication on behalf of the user  
- User sees a successfully completed transaction occurring  

4.OpenID is for humans logging into machines. It was to serve as a single sign in, vouching for the identities of users.

## [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)  

1. Authentication is the process of verifying a user's identity. Authorization is the process of determining wheather a user is authorized to perform an action or access a resource.  

2. Authorization Code Flow is the process of exchanging an Authorization code for an access token  

3. Authorization Code Flow with Proof Key for Code Exchange follows the Authorization Code Flow with an additional step where a random, unique verifier is generated along with a code challenge which is sent for authorization, before recieving an access token  

4. Implicit Flow with Form Post is for apps which are unable to securely store Client Secrets  

5. Client Credentials Flow is when the system authenticates and authorizes the app rather than a user  

6. Device Authorization Flow is when rather than authenticating the user directly, the device asks the user to go to a link and authorize the device  

7. Resource Owner Password Flow requests that users provide credentials (username and password)  

## Things I want to know more about  

-
