[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [AuthorizationCodeAccessTokenGenerator](index.md) / [generate](./generate.md)

# generate

`fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../../org.http4k.security.oauth.server/-client-id/index.md)`, tokenRequest: `[`TokenRequest`](../../org.http4k.security.oauth.server/-token-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AuthorizationCodeAccessTokenGenerator.kt#L31)

Overrides [AccessTokenGenerator.generate](../-access-token-generator/generate.md)


`fun generate(request: `[`AuthorizationCodeAccessTokenRequest`](../-authorization-code-access-token-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/AuthorizationCodeAccessTokenGenerator.kt#L34)