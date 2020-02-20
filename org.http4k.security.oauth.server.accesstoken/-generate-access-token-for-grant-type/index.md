[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [GenerateAccessTokenForGrantType](./index.md)

# GenerateAccessTokenForGrantType

`class GenerateAccessTokenForGrantType` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/GenerateAccessTokenForGrantType.kt#L25)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GenerateAccessTokenForGrantType(authorizationCodes: `[`AuthorizationCodes`](../../org.http4k.security.oauth.server/-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../../org.http4k.security.oauth.server/-access-tokens/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)`, idTokens: `[`IdTokens`](../../org.http4k.security.oauth.server/-id-tokens/index.md)`, refreshTokens: `[`RefreshTokens`](../../org.http4k.security.oauth.server.refreshtoken/-refresh-tokens/index.md)`, grantTypes: `[`GrantTypesConfiguration`](../-grant-types-configuration/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [generate](generate.md) | `fun generate(request: `[`Request`](../../org.http4k.core/-request/index.md)`): Result<`[`AccessTokenDetails`](../../org.http4k.security/-access-token-details/index.md)`, `[`AccessTokenError`](../../org.http4k.security.oauth.server/-access-token-error.md)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [grantType](grant-type.md) | `val grantType: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [grantTypeForm](grant-type-form.md) | `val grantTypeForm: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
