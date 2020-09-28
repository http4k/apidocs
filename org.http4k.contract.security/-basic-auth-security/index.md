[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [BasicAuthSecurity](./index.md)

# BasicAuthSecurity

`class BasicAuthSecurity : `[`Security`](../-security/index.md)

Checks the presence of basic auth credentials. Filter returns 401 if auth fails.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Checks the presence of basic auth credentials. Filter returns 401 if auth fails.`BasicAuthSecurity(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "basicAuth")` |

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `fun `[`Security`](../-security/index.md)`.and(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |
| [or](../or.md) | `fun `[`Security`](../-security/index.md)`.or(that: `[`Security`](../-security/index.md)`): `[`Security`](../-security/index.md) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [renderer](../../org.http4k.contract.openapi.v2/renderer.md) | `val BasicAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
| [renderer](../../org.http4k.contract.openapi.v3/renderer.md) | `val BasicAuthSecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
