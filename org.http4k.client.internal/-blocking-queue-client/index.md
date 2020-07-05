[http4k](../../index.md) / [org.http4k.client.internal](../index.md) / [BlockingQueueClient](./index.md)

# BlockingQueueClient

`class BlockingQueueClient : WebSocketClient`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BlockingQueueClient(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)`, timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`, draft: Draft, queue: `[`LinkedBlockingQueue`](https://docs.oracle.com/javase/9/docs/api/java/util/concurrent/LinkedBlockingQueue.html)`<() -> `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`?>)` |

### Functions

| Name | Summary |
|---|---|
| [onClose](on-close.md) | `fun onClose(code: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, remote: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onError](on-error.md) | `fun onError(e: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMessage](on-message.md) | `fun onMessage(message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun onMessage(bytes: `[`ByteBuffer`](https://docs.oracle.com/javase/9/docs/api/java/nio/ByteBuffer.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onOpen](on-open.md) | `fun onOpen(sh: ServerHandshake): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
