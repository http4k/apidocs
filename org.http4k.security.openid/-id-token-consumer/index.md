[http4k](../../index.md) / [org.http4k.security.openid](../index.md) / [IdTokenConsumer](./index.md)

# IdTokenConsumer

`interface IdTokenConsumer`

### Functions

| Name | Summary |
|---|---|
| [consumeFromAccessTokenResponse](consume-from-access-token-response.md) | `abstract fun consumeFromAccessTokenResponse(idToken: `[`IdToken`](../-id-token/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [consumeFromAuthorizationResponse](consume-from-authorization-response.md) | `abstract fun consumeFromAuthorizationResponse(idToken: `[`IdToken`](../-id-token/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [nonceFromIdToken](nonce-from-id-token.md) | `abstract fun nonceFromIdToken(idToken: `[`IdToken`](../-id-token/index.md)`): `[`Nonce`](../-nonce/index.md)`?` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [NoOp](-no-op.md) | `val NoOp: `[`IdTokenConsumer`](./index.md) |
