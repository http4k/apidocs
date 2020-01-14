[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](./index.md)

# OAuthPersistence

`interface OAuthPersistence` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/OAuthPersistence.kt#L13)

Provides persistence for OAuth lifecycle values:

* CrossSiteRequestForgeryToken - used to retrieve that authorisation code assignment responses are genuinely from the end-service.
* AccessToken - provides time-limited access to protected API resources on the end-service.

### Functions

| Name | Summary |
|---|---|
| [assignCsrf](assign-csrf.md) | `abstract fun assignCsrf(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, csrf: `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a CSRF token to this OAuth auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens. |
| [assignNonce](assign-nonce.md) | `abstract fun assignNonce(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a nonce to this OIDC auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens. |
| [assignToken](assign-token.md) | `abstract fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessToken`](../-access-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign the swapped AccessToken returned by the end-service. Opportunity here to modify the response returned to the user when the redirection happens. |
| [authFailureResponse](auth-failure-response.md) | `open fun authFailureResponse(): `[`Response`](../../org.http4k.core/-response/index.md)<br>Build the default failure response which occurs when a failure occurs during the callback process (eg. a mismatch/missing CSRF or failure occurring when calling into the end-service for the access-token. |
| [retrieveCsrf](retrieve-csrf.md) | `abstract fun retrieveCsrf(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`?`<br>Retrieve the stored CSRF token for this user request |
| [retrieveNonce](retrieve-nonce.md) | `abstract fun retrieveNonce(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?`<br>Retrieve the stored nonce token for this user request |
| [retrieveToken](retrieve-token.md) | `abstract fun retrieveToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AccessToken`](../-access-token/index.md)`?`<br>Retrieve the stored AccessToken token for this user request |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [InsecureCookieBasedOAuthPersistence](../-insecure-cookie-based-o-auth-persistence/index.md) | `class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](./index.md)<br>This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production! |
