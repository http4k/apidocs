[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokens](index.md) / [create](./create.md)

# create

`abstract fun create(authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AuthorizationCodeAlreadyUsed`](../-authorization-code-already-used.md)`>`

Creates a new access token for a valid authorization code.

`abstract fun create(clientId: `[`ClientId`](../-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../-token-request/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AccessTokenError`](../-access-token-error.md)`>`

creates a new access token for a given client.

