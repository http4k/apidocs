[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](index.md) / [assignToken](./assign-token.md)

# assignToken

`abstract fun assignToken(request: `[`Request`](../../org.http4k.core/-request/index.md)`, redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, accessToken: `[`AccessToken`](../-access-token/index.md)`, idToken: `[`IdToken`](../../org.http4k.security.openid/-id-token/index.md)`? = null): `[`Response`](../../org.http4k.core/-response/index.md)

Assign the swapped AccessToken (and optional IdToken) returned by the end-service. Opportunity here to modify the
response returned to the user when the redirection happens.

Notice that both accessToken and idToken contain the raw response from the authorization server and may
require extra validation before use.

