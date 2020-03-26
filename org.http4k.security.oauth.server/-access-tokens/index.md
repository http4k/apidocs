[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokens](./index.md)

# AccessTokens

`interface AccessTokens`

Provides a consistent way to generate access tokens.

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | Creates a new access token for a valid authorization code.`abstract fun create(clientId: `[`ClientId`](../-client-id/index.md)`, tokenRequest: `[`AuthorizationCodeAccessTokenRequest`](../../org.http4k.security.oauth.server.accesstoken/-authorization-code-access-token-request/index.md)`, authorizationCode: `[`AuthorizationCode`](../-authorization-code/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AuthorizationCodeAlreadyUsed`](../-authorization-code-already-used.md)`>`<br>creates a new access token for a given client.`abstract fun create(clientId: `[`ClientId`](../-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../-token-request/index.md)`): Result<`[`AccessToken`](../../org.http4k.security/-access-token/index.md)`, `[`AccessTokenError`](../-access-token-error.md)`>` |
