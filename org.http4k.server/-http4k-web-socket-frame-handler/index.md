[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kWebSocketFrameHandler](./index.md)

# Http4kWebSocketFrameHandler

`class Http4kWebSocketFrameHandler : FrameHandler`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kWebSocketFrameHandler(wSocket: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)`, upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [onClosed](on-closed.md) | `fun onClosed(closeStatus: CloseStatus, callback: Callback): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onError](on-error.md) | `fun onError(cause: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`, callback: Callback): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onFrame](on-frame.md) | `fun onFrame(frame: Frame, callback: Callback): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onOpen](on-open.md) | `fun onOpen(session: CoreSession, callback: Callback): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
