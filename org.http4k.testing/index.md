[http4k](../index.md) / [org.http4k.testing](./index.md)

## Package org.http4k.testing

Useful tools for testing http4k applications.

### Types

| Name | Summary |
|---|---|
| [RecordingEvents](-recording-events/index.md) | `class RecordingEvents : `[`Events`](../org.http4k.core/-events.md)`, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Event`](../org.http4k.core/-event/index.md)`>`<br>Simple recording events that can be used in tests |
| [TestWsClient](-test-ws-client/index.md) | `class TestWsClient : `[`WsClient`](-ws-client/index.md)<br>A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls are routed synchronously to the receiving Websocket, and error are propagated to the caller. |
| [WsClient](-ws-client/index.md) | `interface WsClient` |

### Exceptions

| Name | Summary |
|---|---|
| [ClosedWebsocket](-closed-websocket/index.md) | `data class ClosedWebsocket : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [testWsClient](test-ws-client.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.testWsClient(request: `[`Request`](../org.http4k.core/-request/index.md)`): `[`TestWsClient`](-test-ws-client/index.md)`?` |
