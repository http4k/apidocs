[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [BearerAuthSecurity](./index.md)

# BearerAuthSecurity

`class BearerAuthSecurity : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/BearerAuthSecurity.kt#L10)

Checks the presence of bearer auth credentials. Filter returns 401 if auth fails.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BearerAuthSecurity(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`BearerAuthSecurity(token: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`)`<br>`BearerAuthSecurity(key: `[`RequestContextLens`](../../org.http4k.lens/-request-context-lens.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>, lookup: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
