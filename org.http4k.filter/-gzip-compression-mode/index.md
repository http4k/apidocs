[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GzipCompressionMode](./index.md)

# GzipCompressionMode

`enum class GzipCompressionMode` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ext.kt#L14)

### Enum Values

| Name | Summary |
|---|---|
| [NON_STREAMING](-n-o-n_-s-t-r-e-a-m-i-n-g.md) |  |
| [STREAMING](-s-t-r-e-a-m-i-n-g.md) |  |

### Properties

| Name | Summary |
|---|---|
| [compress](compress.md) | `val compress: (`[`Body`](../../org.http4k.core/-body/index.md)`) -> `[`Body`](../../org.http4k.core/-body/index.md) |
| [decompress](decompress.md) | `val decompress: (`[`Body`](../../org.http4k.core/-body/index.md)`) -> `[`Body`](../../org.http4k.core/-body/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
