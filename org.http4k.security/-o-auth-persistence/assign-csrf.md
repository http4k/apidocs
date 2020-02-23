[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](index.md) / [assignCsrf](./assign-csrf.md)

# assignCsrf

`abstract fun assignCsrf(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, csrf: `[`CrossSiteRequestForgeryToken`](../-cross-site-request-forgery-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)

Assign a CSRF token to this OAuth auth redirection (to the end-service) response. Opportunity here to modify the
response returned to the user when the redirection happens.

