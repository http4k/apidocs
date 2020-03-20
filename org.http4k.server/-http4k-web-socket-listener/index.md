[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kWebSocketListener](./index.md)

# Http4kWebSocketListener

`class Http4kWebSocketListener : WebSocketListener`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kWebSocketListener(wSocket: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)`, upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [onWebSocketBinary](on-web-socket-binary.md) | `fun onWebSocketBinary(payload: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`, offset: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, len: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onWebSocketClose](on-web-socket-close.md) | `fun onWebSocketClose(statusCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onWebSocketConnect](on-web-socket-connect.md) | `fun onWebSocketConnect(session: Session): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onWebSocketError](on-web-socket-error.md) | `fun onWebSocketError(cause: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onWebSocketText](on-web-socket-text.md) | `fun onWebSocketText(message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
