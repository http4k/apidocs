[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [BasicAuthSecurity](./index.md)

# BasicAuthSecurity

`class BasicAuthSecurity : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/BasicAuthSecurity.kt#L10)

Checks the presence of basic auth credentials. Filter returns 401 if auth fails.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BasicAuthSecurity(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../org.http4k.core/-credentials/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "basicAuth")`<br>Checks the presence of basic auth credentials. Filter returns 401 if auth fails. |

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
