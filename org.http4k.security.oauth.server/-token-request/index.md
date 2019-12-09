[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [TokenRequest](./index.md)

# TokenRequest

`data class TokenRequest` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/TokenRequest.kt#L6)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TokenRequest(grantType: `[`GrantType`](../../org.http4k.security.oauth.server.accesstoken/-grant-type/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`?, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, clientAssertionType: `[`Uri`](../../org.http4k.core/-uri/index.md)`?, clientAssertion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [clientAssertion](client-assertion.md) | `val clientAssertion: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [clientAssertionType](client-assertion-type.md) | `val clientAssertionType: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [clientId](client-id.md) | `val clientId: `[`ClientId`](../-client-id/index.md)`?` |
| [clientSecret](client-secret.md) | `val clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [grantType](grant-type.md) | `val grantType: `[`GrantType`](../../org.http4k.security.oauth.server.accesstoken/-grant-type/index.md) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
