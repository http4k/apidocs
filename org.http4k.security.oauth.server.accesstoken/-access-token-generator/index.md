[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AccessTokenGenerator](./index.md)

# AccessTokenGenerator

`interface AccessTokenGenerator`

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `abstract fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationCodeAccessTokenGenerator](../-authorization-code-access-token-generator/index.md) | `class AuthorizationCodeAccessTokenGenerator : `[`AccessTokenGenerator`](./index.md) |
| [ClientCredentialsAccessTokenGenerator](../-client-credentials-access-token-generator/index.md) | `class ClientCredentialsAccessTokenGenerator : `[`AccessTokenGenerator`](./index.md) |
| [RefreshTokenAccessTokenGenerator](../../org.http4k.security.oauth.server.refreshtoken/-refresh-token-access-token-generator/index.md) | `class RefreshTokenAccessTokenGenerator : `[`AccessTokenGenerator`](./index.md) |
