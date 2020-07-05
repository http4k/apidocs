[http4k](../../index.md) / [org.http4k.client.internal](../index.md) / [BlockingWsClient](./index.md)

# BlockingWsClient

`class BlockingWsClient : `[`WsClient`](../../org.http4k.websocket/-ws-client/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BlockingWsClient(queue: `[`LinkedBlockingQueue`](https://docs.oracle.com/javase/9/docs/api/java/util/concurrent/LinkedBlockingQueue.html)`<() -> `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`?>, client: `[`BlockingQueueClient`](../-blocking-queue-client/index.md)`, autoReconnection: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(status: `[`WsStatus`](../../org.http4k.websocket/-ws-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [received](received.md) | `fun received(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`>` |
| [send](send.md) | `fun send(message: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
