[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](./index.md)

# InsecureCookieBasedOAuthPersistence

`class InsecureCookieBasedOAuthPersistence : `[`OAuthPersistence`](../-o-auth-persistence/index.md)

This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie.
Access-tokens for end-services are fully available to the browser so do not use this in production!

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie. Access-tokens for end-services are fully available to the browser so do not use this in production!`InsecureCookieBasedOAuthPersistence(cookieNamePrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, cookieValidity: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = Duration.ofHours(1), clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC())` |

### Functions

| Name | Summary |
|---|---|
| [assignCsrf](assign-csrf.md) | Assign a CSRF token to this OAuth auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens.`fun assignCsrf(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, csrf: `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [assignNonce](assign-nonce.md) | Assign a nonce to this OIDC auth redirection (to the end-service) response. Opportunity here to modify the response returned to the user when the redirection happens.`fun assignNonce(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [assignToken](assign-token.md) | Assign the swapped AccessToken returned by the end-service. Opportunity here to modify the response returned to the user when the redirection happens.`fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessToken`](../-access-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
| [authFailureResponse](auth-failure-response.md) | Build the default failure response which occurs when a failure occurs during the callback process (eg. a mismatch/missing CSRF or failure occurring when calling into the end-service for the access-token.`fun authFailureResponse(): `[`Response`](../../org.http4k.core/-response/index.md) |
| [retrieveCsrf](retrieve-csrf.md) | Retrieve the stored CSRF token for this user request`fun retrieveCsrf(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`?` |
| [retrieveNonce](retrieve-nonce.md) | Retrieve the stored nonce token for this user request`fun retrieveNonce(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`?` |
| [retrieveToken](retrieve-token.md) | Retrieve the stored AccessToken token for this user request`fun retrieveToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AccessToken`](../-access-token/index.md)`?` |
