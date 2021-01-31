[http4k](../index.md) / [org.http4k.websocket](./index.md)

## Package org.http4k.websocket

Common code relevant to websocket implementations.

### Types

| Name | Summary |
|---|---|
| [PolyHandler](-poly-handler.md) | `typealias ~~PolyHandler~~ = `[`PolyHandler`](../org.http4k.server/-poly-handler/index.md) |
| [PushPullAdaptingWebSocket](-push-pull-adapting-web-socket/index.md) | `abstract class PushPullAdaptingWebSocket : `[`Websocket`](-websocket/index.md) |
| [Websocket](-websocket/index.md) | Represents a connected Websocket instance, and can be passed around an application. This is configured to react to events on the WS event stream by attaching listeners.`interface Websocket` |
| [WsClient](-ws-client/index.md) | `interface WsClient` |
| [WsConsumer](-ws-consumer.md) | `typealias WsConsumer = (`[`Websocket`](-websocket/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [WsHandler](-ws-handler.md) | `typealias WsHandler = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`WsConsumer`](-ws-consumer.md)`?` |
| [WsMessage](-ws-message/index.md) | `data class WsMessage` |
| [WsStatus](-ws-status/index.md) | `data class WsStatus` |
