[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [AccessTokenResult](./index.md)

# AccessTokenResult

`data class AccessTokenResult` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/AccessTokenResult.kt#L5)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenResult(token: `[`AccessTokenContainer`](../../org.http4k.security/-access-token-container/index.md)`? = null, error: `[`AccessTokenCreationError`](../-access-token-creation-error/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [error](error.md) | `val error: `[`AccessTokenCreationError`](../-access-token-creation-error/index.md)`?` |
| [token](token.md) | `val token: `[`AccessTokenContainer`](../../org.http4k.security/-access-token-container/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [isSuccess](is-success.md) | `fun isSuccess(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
