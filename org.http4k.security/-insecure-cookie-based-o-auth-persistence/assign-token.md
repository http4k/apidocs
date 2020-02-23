[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [assignToken](./assign-token.md)

# assignToken

`fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessToken`](../-access-token/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)

Assign the swapped AccessToken returned by the end-service. Opportunity here to modify the
response returned to the user when the redirection happens.

