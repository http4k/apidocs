[http4k](../../index.md) / [org.http4k.security](../index.md) / [AccessTokenDetails](./index.md)

# AccessTokenDetails

`data class AccessTokenDetails` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/AccessTokenContainer.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenDetails(accessToken: `[`AccessTokenContainer`](../-access-token-container/index.md)`, idToken: `[`IdTokenContainer`](../../org.http4k.security.openid/-id-token-container/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | `val accessToken: `[`AccessTokenContainer`](../-access-token-container/index.md) |
| [idToken](id-token.md) | `val idToken: `[`IdTokenContainer`](../../org.http4k.security.openid/-id-token-container/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |