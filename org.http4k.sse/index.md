[http4k](../index.md) / [org.http4k.sse](./index.md)

## Package org.http4k.sse

### Types

| Name | Summary |
|---|---|
| [PushAdaptingSse](-push-adapting-sse/index.md) | `abstract class PushAdaptingSse : `[`Sse`](-sse/index.md) |
| [Sse](-sse/index.md) | `interface Sse` |
| [SseClient](-sse-client/index.md) | `interface SseClient` |
| [SseConsumer](-sse-consumer.md) | `typealias SseConsumer = (`[`Sse`](-sse/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [SseHandler](-sse-handler.md) | `typealias SseHandler = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`SseConsumer`](-sse-consumer.md)`?` |
| [SseMessage](-sse-message/index.md) | `sealed class SseMessage` |
