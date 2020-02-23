[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [ImplicitOAuthSecurity](./index.md)

# ImplicitOAuthSecurity

`class ImplicitOAuthSecurity : `[`OAuthSecurity`](../-o-auth-security/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ImplicitOAuthSecurity(authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](../-o-auth-scope/index.md)`> = emptyList(), filter: `[`Filter`](../../org.http4k.core/-filter/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "oauthSecurityImplicit", refreshUrl: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null, extraFields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [authorizationUrl](authorization-url.md) | `val authorizationUrl: `[`Uri`](../../org.http4k.core/-uri/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `fun `[`Security`](../-security/index.md)`.and(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |
| [or](../or.md) | `fun `[`Security`](../-security/index.md)`.or(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [renderer](../../org.http4k.contract.openapi.v2/renderer.md) | `val ImplicitOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
| [renderer](../../org.http4k.contract.openapi.v3/renderer.md) | `val ImplicitOAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
