[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kWebSocketAdapter](./index.md)

# Http4kWebSocketAdapter

`class Http4kWebSocketAdapter`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kWebSocketAdapter(innerSocket: `[`PushPullAdaptingWebSocket`](../../org.http4k.websocket/-push-pull-adapting-web-socket/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [onClose](on-close.md) | `fun onClose(statusCode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, reason: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onError](on-error.md) | `fun onError(throwable: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMessage](on-message.md) | `fun onMessage(body: `[`Body`](../../org.http4k.core/-body/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
