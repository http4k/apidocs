[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [GenerateAccessToken](./index.md)

# GenerateAccessToken

`class GenerateAccessToken : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GenerateAccessToken(authorizationCodes: `[`AuthorizationCodes`](../-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../-access-tokens/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)`, idTokens: `[`IdTokens`](../-id-tokens/index.md)`, refreshTokens: `[`RefreshTokens`](../../org.http4k.security.oauth.server.refreshtoken/-refresh-tokens/index.md)`, errorRenderer: `[`JsonResponseErrorRenderer`](../-json-response-error-renderer/index.md)`, grantTypes: `[`GrantTypesConfiguration`](../../org.http4k.security.oauth.server.accesstoken/-grant-types-configuration/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
