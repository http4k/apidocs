[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RequestMeta](./index.md)

# RequestMeta

`class RequestMeta : `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L25)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RequestMeta(request: `[`Request`](../../org.http4k.core/-request/index.md)`, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, example: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`? = null)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [definitionId](../-http-message-meta/definition-id.md) | `val definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [description](../-http-message-meta/description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [example](../-http-message-meta/example.md) | `val example: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [message](../-http-message-meta/message.md) | `val message: `[`T`](../-http-message-meta/index.md#T) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
