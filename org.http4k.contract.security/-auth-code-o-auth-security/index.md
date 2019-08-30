[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [AuthCodeOAuthSecurity](./index.md)

# AuthCodeOAuthSecurity

`class AuthCodeOAuthSecurity : `[`OAuthSecurity`](../-o-auth-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/OAuthSecurity.kt#L15)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthCodeOAuthSecurity(authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`, tokenUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`> = emptyList(), filter: `[`Filter`](../../org.http4k.core/-filter/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "oauthSecurityAuthCode", refreshUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null, extraFields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [authorizationUrl](authorization-url.md) | `val authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md) |
| [tokenUrl](token-url.md) | `val tokenUrl: `[`Uri`](../../org.http4k.core/-uri/index.md) |

### Inherited Properties

| Name | Summary |
|---|---|
| [extraFields](../-o-auth-security/extra-fields.md) | `val extraFields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [filter](../-o-auth-security/filter.md) | `open val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](../-o-auth-security/name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [refreshUrl](../-o-auth-security/refresh-url.md) | `val refreshUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`?` |
| [scopes](../-o-auth-security/scopes.md) | `val scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(oAuthProvider: `[`OAuthProvider`](../../org.http4k.security/-o-auth-provider/index.md)`, customScopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`>? = null): `[`AuthCodeOAuthSecurity`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `fun `[`Security`](../-security/index.md)`.and(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |
| [or](../or.md) | `fun `[`Security`](../-security/index.md)`.or(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [renderer](../../org.http4k.contract.openapi.v3/renderer.md) | `val AuthCodeOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
