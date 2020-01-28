[http4k](../../index.md) / [org.http4k.security.oauth.server.request](../index.md) / [Claims](./index.md)

# Claims

`data class Claims` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/request/RequestObject.kt#L36)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Claims(userInfo: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Claim`](../-claim/index.md)`>? = null, idToken: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Claim`](../-claim/index.md)`>? = null)` |

### Properties

| Name | Summary |
|---|---|
| [idToken](id-token.md) | `val idToken: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Claim`](../-claim/index.md)`>?` |
| [userInfo](user-info.md) | `val userInfo: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Claim`](../-claim/index.md)`>?` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
