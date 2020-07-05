[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [WsClient](./index.md)

# WsClient

`interface WsClient`

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `abstract fun close(status: `[`WsStatus`](../-ws-status/index.md)` = NORMAL): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [received](received.md) | `abstract fun received(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`WsMessage`](../-ws-message/index.md)`>` |
| [send](send.md) | `abstract fun send(message: `[`WsMessage`](../-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [BlockingWsClient](../../org.http4k.client.internal/-blocking-ws-client/index.md) | `class BlockingWsClient : `[`WsClient`](./index.md) |
| [TestWsClient](../../org.http4k.testing/-test-ws-client/index.md) | A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls are routed synchronously to the receiving Websocket, and error are propagated to the caller.`class TestWsClient : `[`WsClient`](./index.md) |
