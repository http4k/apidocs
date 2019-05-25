[http4k](../../index.md) / [org.http4k.security.openid](../index.md) / [RequestJwts](./index.md)

# RequestJwts

`interface RequestJwts` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/openid/RequestJwts.kt#L5)

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `abstract fun create(authRequest: `[`AuthRequest`](../../org.http4k.security.oauth.server/-auth-request/index.md)`, state: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RequestJwtContainer`](../-request-jwt-container/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |