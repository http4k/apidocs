[http4k](../../index.md) / [org.http4k.security](../index.md) / [AccessTokenDetails](./index.md)

# AccessTokenDetails

`data class AccessTokenDetails` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/AccessToken.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AccessTokenDetails(accessToken: `[`AccessToken`](../-access-token/index.md)`, idToken: `[`IdToken`](../../org.http4k.security.openid/-id-token/index.md)`? = null, scope: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [accessToken](access-token.md) | `val accessToken: `[`AccessToken`](../-access-token/index.md) |
| [idToken](id-token.md) | `val idToken: `[`IdToken`](../../org.http4k.security.openid/-id-token/index.md)`?` |
| [scope](scope.md) | `val scope: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
