[http4k](../../index.md) / [org.http4k.contract](../index.md) / [JsonErrorResponseRenderer](./index.md)

# JsonErrorResponseRenderer

`class JsonErrorResponseRenderer<NODE> : `[`ErrorResponseRenderer`](../-error-response-renderer/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/contract/ErrorResponseRenderer.kt#L17)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonErrorResponseRenderer(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [badRequest](bad-request.md) | `fun badRequest(failures: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../../org.http4k.lens/-failure/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |
| [notFound](not-found.md) | `fun notFound(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
