[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthPersistence](index.md) / [assignOriginalUri](./assign-original-uri.md)

# assignOriginalUri

`abstract fun assignOriginalUri(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, originalUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)

opportunity to store the uri that the request was made before authentication
this will then be redirected back to after auth

Be careful not to create scenarios where an open redirector is created,
by applications attempting some sort of phishing attack

