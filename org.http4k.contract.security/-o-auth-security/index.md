[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [OAuthSecurity](./index.md)

# OAuthSecurity

`data class OAuthSecurity : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/OAuthSecurity.kt#L7)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthSecurity(authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`, tokenUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`> = emptyList(), filter: `[`Filter`](../../org.http4k.core/-filter/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "oauthSecurity")` |

### Properties

| Name | Summary |
|---|---|
| [authorizationUrl](authorization-url.md) | `val authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`>` |
| [tokenUrl](token-url.md) | `val tokenUrl: `[`Uri`](../../org.http4k.core/-uri/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(oAuthProvider: `[`OAuthProvider`](../../org.http4k.security/-o-auth-provider/index.md)`, customScopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`>? = null): `[`OAuthSecurity`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
