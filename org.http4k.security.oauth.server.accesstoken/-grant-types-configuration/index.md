[http4k](../../index.md) / [org.http4k.security.oauth.server.accesstoken](../index.md) / [GrantTypesConfiguration](./index.md)

# GrantTypesConfiguration

`data class GrantTypesConfiguration` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/accesstoken/GrantConfiguration.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GrantTypesConfiguration(supportedGrantTypes: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`GrantType`](../-grant-type/index.md)`, `[`AccessTokenRequestAuthentication`](../-access-token-request-authentication/index.md)`>)` |

### Properties

| Name | Summary |
|---|---|
| [supportedGrantTypes](supported-grant-types.md) | `val supportedGrantTypes: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`GrantType`](../-grant-type/index.md)`, `[`AccessTokenRequestAuthentication`](../-access-token-request-authentication/index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [default](default.md) | `fun default(requestAuthentication: `[`AccessTokenRequestAuthentication`](../-access-token-request-authentication/index.md)`): `[`GrantTypesConfiguration`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
