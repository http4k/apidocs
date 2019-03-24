[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Authority](./index.md)

# Authority

`data class Authority` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Authority.kt#L3)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Authority(host: `[`Host`](../-host/index.md)`, port: `[`Port`](../-port/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [host](host.md) | `val host: `[`Host`](../-host/index.md) |
| [port](port.md) | `val port: `[`Port`](../-port/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Authority`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
