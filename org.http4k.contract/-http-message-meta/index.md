[http4k](../../index.md) / [org.http4k.contract](../index.md) / [HttpMessageMeta](./index.md)

# HttpMessageMeta

`open class HttpMessageMeta<out T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpMessageMeta(message: T, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, example: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [definitionId](definition-id.md) | `val definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [example](example.md) | `val example: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [message](message.md) | `val message: T` |

### Inheritors

| Name | Summary |
|---|---|
| [RequestMeta](../-request-meta/index.md) | `class RequestMeta : `[`HttpMessageMeta`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>` |
| [ResponseMeta](../-response-meta/index.md) | `class ResponseMeta : `[`HttpMessageMeta`](./index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>` |
