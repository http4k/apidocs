[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [OAuthSecurity](./index.md)

# OAuthSecurity

`sealed class OAuthSecurity : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/OAuthSecurity.kt#L7)

### Properties

| Name | Summary |
|---|---|
| [extraFields](extra-fields.md) | `val extraFields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [filter](filter.md) | `open val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [refreshUrl](refresh-url.md) | `val refreshUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [scopes](scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [googleCloudEndpoints](../google-cloud-endpoints.md) | `fun OAuthSecurity.Companion.googleCloudEndpoints(issuer: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, jwksUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, audiences: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`ImplicitOAuthSecurity`](../-implicit-o-auth-security/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AuthCodeOAuthSecurity](../-auth-code-o-auth-security/index.md) | `class AuthCodeOAuthSecurity : `[`OAuthSecurity`](./index.md) |
| [ImplicitOAuthSecurity](../-implicit-o-auth-security/index.md) | `class ImplicitOAuthSecurity : `[`OAuthSecurity`](./index.md) |
