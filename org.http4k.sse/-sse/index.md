[http4k](../../index.md) / [org.http4k.sse](../index.md) / [Sse](./index.md)

# Sse

`interface Sse`

### Properties

| Name | Summary |
|---|---|
| [connectRequest](connect-request.md) | `abstract val connectRequest: `[`Request`](../../org.http4k.core/-request/index.md) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `abstract fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onClose](on-close.md) | `abstract fun onClose(fn: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [send](send.md) | `abstract fun send(message: `[`SseMessage`](../-sse-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [PushAdaptingSse](../-push-adapting-sse/index.md) | `abstract class PushAdaptingSse : `[`Sse`](./index.md) |
