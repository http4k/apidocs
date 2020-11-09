[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](./index.md)

# OAuthPersistence

`interface OAuthPersistence`

Provides persistence for OAuth lifecycle values:

* CrossSiteRequestForgeryToken - used to retrieve that authorisation code assignment responses are genuinely from the end-service.
* AccessToken - provides time-limited access to protected API resources on the end-service.

### Functions

| Name | Summary |
|---|---|
| [assignCsrf](assign-csrf.md) | Assign a CSRF token to this OAuth auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens.`abstract fun assignCsrf(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, csrf: `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [assignNonce](assign-nonce.md) | Assign a nonce to this OIDC auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens.`abstract fun assignNonce(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [assignOriginalUri](assign-original-uri.md) | opportunity to store the uri that the request was made before authentication this will then be redirected back to after auth`abstract fun assignOriginalUri(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, originalUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [assignToken](assign-token.md) | Assign the swapped AccessToken returned by the end-service. Opportunity here to modify the response returned to the user when the redirection happens.`abstract fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessToken`](../-access-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [authFailureResponse](auth-failure-response.md) | Build the default failure response which occurs when a failure occurs during the callback process (eg. a mismatch/missing CSRF or failure occurring when calling into the end-service for the access-token.`open fun authFailureResponse(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [retrieveCsrf](retrieve-csrf.md) | Retrieve the stored CSRF token for this user request`abstract fun retrieveCsrf(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`?` |
| [retrieveNonce](retrieve-nonce.md) | Retrieve the stored nonce token for this user request`abstract fun retrieveNonce(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?` |
| [retrieveOriginalUri](retrieve-original-uri.md) | Retrieve the stored original uri for this user request`abstract fun retrieveOriginalUri(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [retrieveToken](retrieve-token.md) | Retrieve the stored AccessToken token for this user request`abstract fun retrieveToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AccessToken`](../-access-token/index.md)`?` |

### Inheritors

| Name | Summary |
|---|---|
| [InsecureCookieBasedOAuthPersistence](../-insecure-cookie-based-o-auth-persistence/index.md) | This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production!`class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](./index.md) |
