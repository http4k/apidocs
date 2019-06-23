[http4k](../../index.md) / [org.http4k.security.openid](../index.md) / [IdTokenConsumer](./index.md)

# IdTokenConsumer

`interface IdTokenConsumer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/openid/IdTokenConsumer.kt#L3)

### Functions

| Name | Summary |
|---|---|
| [consumeFromAccessTokenResponse](consume-from-access-token-response.md) | `abstract fun consumeFromAccessTokenResponse(idToken: `[`IdToken`](../-id-token/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [consumeFromAuthorizationResponse](consume-from-authorization-response.md) | `abstract fun consumeFromAuthorizationResponse(idToken: `[`IdToken`](../-id-token/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [NoOp](-no-op.md) | `val NoOp: `[`IdTokenConsumer`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
